---
CharClass: "[[Abjurer|Abjurer]]"
Class: "[[Diviner|Diviner]]"
---
## This page is just for me to test out Code

&& p.MagicItems && !p.MagicItems.includes("+1")

```dataviewjs
dv.list(dv.pages()
		.where(p => p.Status && p.Status.includes("Active") && p.Role && p.Role.includes("Player"))
		.MagicItems.distinct())
```

xxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(
  dv.pages()
    .where(p => 
      p.Status && p.Status.includes("Active") &&
      p.Role && p.Role.includes("Player") &&
      p.MagicItems
    )
    .map(p => 
      p.MagicItems.filter(MagicItems => !p.MagicItems.includes("+"))
    )
    .distinct()
)
```

xxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(
  dv.pages()
    .where(p => 
      p.Status && p.Status.includes("Active") &&
      p.Role && p.Role.includes("Player") &&
      p.MagicItems
    )
    .map(p => Array.from(p.MagicItems || [])
    .filter(MagicItems => !p.MagicItems.includes("+"))
    )
    .distinct()
)
```

xxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(
  dv.pages()
    .where(p => p.Status && p.Status.includes("Active") && 
               p.Role && p.Role.includes("Player") && 
               p.MagicItems)
    .to("MagicItems")  // Maps to the MagicItems field and flattens
	.filter(p => !(p.MagicItems.includes("+") && p.MagicItems.indexOf("+") === 0))
    .distinct()
)
```

xxxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(
  dv.pages()
    .where(p => p.Status && p.Status.includes("Active") && 
               p.Role && p.Role.includes("Player") && 
               p.MagicItems)
    .MagicItems
    .where(p => p.MagicItems && !p.MagicItems.includes("+"))
    .distinct()
)
```

xxxxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(dv.pages()
		.where(p => p.Status && p.Status.includes("Active") && p.Role && p.Role.includes("Player") && p.MagicItems && !p.MagicItems.includes("+"))
		.MagicItems.distinct())
```

xxxxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(dv.pages()
		.where(p => p.Status && p.Status.includes("Active") && p.Role && p.Role.includes("Player") && p.MagicItems && !p.MagicItems.some(MagicItems => String(MagicItems).includes("+")))
		.MagicItems.distinct())
```

xxxxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(dv.pages()
		.where(p => p.Status && p.Status.includes("Active") && p.Role && p.Role.includes("Player") && p.MagicItems && !p.MagicItems.some(MagicItems => p.MagicItems.includes("+")))
		.MagicItems.distinct())
```

xxxxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(
  dv.pages()
    .where(p => 
      p.Status && p.Status.includes("Active") &&
      p.Role && p.Role.includes("Player") &&
      p.MagicItems
    )
    .flatMap(p => 
      p.MagicItems.filter(item => !String(item).includes("+"))
    )
    .distinct()
)
```

xxxxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(
  dv.pages()
    .where(p => 
      p.Status && p.Status.includes("Active") &&
      p.Role && p.Role.includes("Player") &&
      p.MagicItems
    )
    .flatMap(p => 
      p.MagicItems.filter(item =>
		    !(
			    String(item).includes("+") ||
			    String(item).includes("(")
			)
		)
    )
    .distinct()
)
```

xxxxxxxxxxxxxxxxxxxxx

```dataviewjs
dv.list(
  dv.pages()
    .where(p => 
      p.Status && p.Status.includes("Active") &&
      p.Role && p.Role.includes("Player") &&
      p.MagicItems
    )
    .flatMap(p => 
      p.MagicItems
        .filter(item =>
          !String(item).includes("+")
        )
        .map(item =>
          String(item).replace(/\s*\([^)]*\)$/, "")
        )
    )
    .distinct()
)
```