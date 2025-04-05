---
banner: "[[PlayerBanner.jpg]]"
banner-y: 95
content-start: 175
banner-display: cover
banner-repeat: false
banner-height: 250
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 67
---
## Permanent Players
```dataview
TABLE WITHOUT ID link(file.name) AS "Player Name"
from "3-Party/Players"
where (file.name != "Players") 
where (PlayerRole = "Permanent") 
```

## Supporting Players & Guests
```dataview
TABLE WITHOUT ID link(file.name) AS "Player Name"
from "3-Party/Players"
where (file.name != "Players") 
where (PlayerRole = "Guest") 
```
