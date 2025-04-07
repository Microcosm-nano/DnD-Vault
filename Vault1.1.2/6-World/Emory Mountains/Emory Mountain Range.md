---
banner: "[[Emory.jpg]]"
map_height_y: 2048
map_width_x: 2048
scale_pixels: 50
scale_pixels_range: 50
mapCalc1: 10
NoteIcon: map
banner-y: 45
content-start: 175
banner-display: cover
banner-repeat: false
banner-height: 250
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 100
---

```leaflet
id: Emory ### Must be unique with no spaces
image: [[Emory Mountain Range Map New.jpg]] ### Link to the map image file
bounds: [[0,0], [1536, 2048]] ### Size of the map in px Width_x, Height_y
height: 1000px ### Size of the leaflet embed in px on your screen
width: 95% ### Size of the leaflet embed in your note
lat: 1024 ### To center the map, make this half of the map width. 
long: 1024 ### To center the map, make this half of the map height. 
minZoom: -.8 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level. 
maxZoom: 1 ### Controls how far towards the map you can zoom in.  Hover over the target icon to see the current level. 
defaultZoom: -.8 ### Sets the default zoom level when the map loads.  Hover over the target icon to see the current level. 
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out. 
unit: m ### The value displayed when measuring so you know what type of unit is being measure.
scale: .2 ### Real units/px (resolution) of your map
recenter: true
darkmode: false ###

```

## Overview

The Emory Mountain Range is a geographic region in the Kingdom known as Vetterlund. Vetterlund is located on the continent of Ossë and serves as a vassal state of the Azlaphate Empire. It is populated with tall mountains known sometimes as the "Emorites" by the locals, known by their country's demonym as "Vetters".

## Scenery
> [!tip]- Gallery
![[Emory.jpg|600]]     ![[Emory1.jpg|650]]     ![[Emory2.jpg|600]]
>
>*The Emorites stand tall above the rest of the Vetterlund. The lofty peaks and rolling hills make for beautiful vistas, while much of the mountainside is covered in sprawling forests and plentiful streams  from snowmelt*

## Etymology

Vetterlund comes from the Eldercommon "Veter", meaning: father, brother, male cousin, or male comrade. Lund comes from the Eldercommon "Lünd", meaning: Grove, land, or forest. It is interpreted by scholars to have literally meant "Grove of our brothers", but would be contextually interpreted to "The Fatherland". Emory comes from the Eldercommon "Emery", meaning: strength, power, or powerful ruler. It is speculated the Emorites were so named because they "rule" over the region with their height and vastness.

## Geography and Major Cities

> [!infobox| right]
> # Settlements in the Emory Mountains
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Settlements "
where contains( region, [[Emory Mountain Range]])
LIMIT 20

The Emory Mountain Range is located in the Northwestern portion of the Vetterlund, flanked to it's East by Faren Luriss, Azlan to the West, Ojanlë to the South, and the Eatern Sea to the North. The Emorites are rich in ores and metals due to their long geological history and despite being one of the oldest mountain ranges in Toril, the Emorites have for one reason or another, resisted the effects of weathering over time. In addition to the mountain peaks, the mountain range is home to many forests, meadows, and dramatic canyons, forming a complex watershed feeding into the Rhahassë river. The Emorites host a complex ecosystem supporting a wide variety of life.

> [!tip]- Gallery
![[Emory3.jpg|800]]     ![[Mine.jpg|300]]
>
>*Picturesque towns dot the mountainside, constructed from locally sourced materials and [[human-xphb#Description|Human]] Vetter architectural styles. Many of these mountain towns will have long, winding paths up the mountains, leading to the mines that support them.*

The largest settlements in the mountain range are:
- [[Herzloch]] - The gateway to the Emory Mountain Pass from [[Lierburg]]
- [[Geldfelder]] - Major economic mining hub and town
- [[Illsprout]] - Major economic agricultural hub, uncharacteristically fertile compared to surrounding region.

## Society

> [!info]- Beliefs and Culture
> ### Beliefs & Culture
The people of the Emory mountain range are cut off from much of the rest of the world and hold strange superstitions and view outsiders with skepticism, particularly those claiming to be holy men, or other various spreaders of faiths. Vetters of the Emory Mountains tend to be polite, but reserved. The laws of hospitality here are very generous, where most homes will feed a guest with copious food and drink, though they will almost never let a guest stay the night. Vetters are also very quick to anger and unite in the face of outsider meddling in their affairs. A prime example of their opposition to outside exploitation would be the [[Miner's Union]], formed in order to hold mining companies accountable to standards of safety and economic stability for their workers. 

> [!info]- Religion
> ### Religion
The Emorites are a very old mountain range, even geologically speaking. They are said to have existed longer than *trees* and used to be part of the *heavens*. There is a strange and indescribable antediluvian mysticism that hangs in the air, and the denizens are drawn to it immensely. Because of this, the Gods are held aloft, yet at a distance. Always kept at an arm's reach away, Vetters look not to the Gods, but to the mountains to interpret the mysteries of the universe. The local Aldermen instead resort to numerous superstitions and pre-arcane rituals to interpret the mysteries of life. It is said by locals to always toss the last sip of your beer for the spirits. They say to look out for the people with antlers and moon shaped pupils to guide you away from trouble. They say to leave food on your doorstep in case the many-mouthed man comes to your home, hungry and upset. The superstitions are numerous, and often too old or ambiguous to speculate an origin.

> [!info]- Economy
> ### Economy
The Emory mountain range famously provides a massive amount of salt, coal, gold, and other mined materials to the rest of the continent. Despite lacking in "cash mineral" resources such as gems and [[mithral-armor-xdmg|Mithral]], more often mined by the [[dwarf-xphb|Dwarves]], Vetterlund's mining industry thrives in the Emorites. A network of mines, processing facilities, and transport networks brings the Emorites an incredible amount of revenue, earning Vetterlund the nickname of "The Mint" of the Azlaphate Empire.

> [!info]- Governance & Military
> ### Governance & Military
![[Cuirassiers.jpg|550]]     ![[Infantrymen.jpg|310]]
*Vetterlund Curiassiers and a Vetter Infantrymen. The armies of the Vetterlund are feared and renowned for their fierce warriors and brilliant strategists, but are perhaps known best for their highly organized and standardized military structure. The Vetters are said to weaponize efficiency to it's furthest extent.*
>
The Emory Mountain Range is a geographic region in the kingdom known as Vetterlund. Vetterlund is located on the continent of Ossë and serves as a vassal state of the Azlaphate Empire. As such, the Azlaphates have heavy influence in Vetterlund and are said to have control over the monarchy. Vetterlund itself is governed by a king. The Vetterlund has little effective governance over the mountain region because maintaining a permanent presence there can be costly and ineffective. The notable exception being [[Geldfelder]], where the Vetterlund will spare no expense to occupy due to it's intrinsic relationship with Vetterlund's economy and currency due to it's gold mine. Most other towns and villages in the mountains are governed by a mayor, selected by various democratic processes, or is led by an Alderman, whose experience can be leaned on in times of uncertainty.

## History

Much of Emory Mountain's earliest history was recorded by the [[dwarf-xphb#Description|Dwarves]] who called the sprawling Emorites their home. After a magical plague began to cull [[dwarf-xphb#Description|Dwarven]] populations around 700 years ago, and the massive growth of Humankind in the area, [[human-xphb#Description|Humans]] began to populate and eventually dominate the region in spite of the harsh conditions on the surface. For the last several hundred years, Vetterlund has remained an independent kingdom, warding off enemies and would-be expansionists until around six years ago when The Azlaphate Empire was formed and began to colonize other kingdoms and nations within Ossë. After a two year long war with the Azlaphates, Vetterlund succumbed to major losses and ceded to the Empire as a Vassal. The Emory mountain range has been relatively unaffected by the change, and has only become more autonomous due to the lack of military presence in the region after the losses incurred by the war.
