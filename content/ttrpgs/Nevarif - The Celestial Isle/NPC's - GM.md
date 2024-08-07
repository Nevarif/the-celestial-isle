---
type: 
faction: 
location: 
world: Nevarif - The Celestial Isle
campaign: Nevarif - The Celestial Isle
date: 2024-07-15
description: 
race: 
gender: 
class:
---
# [[NPC's]]

## All NPC's
```dataview
LIST 
FROM "ttrpgs/Nevarif - The Celestial Isle"

WHERE type = "NPC"
```

## NPC's by Location

### [[BludRock]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"BludRock")
SORT file.name ASC
```
### [[Elderbarough]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"Elderbarough")
SORT file.name ASC
```
### [[Richmond]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"Richmond")
SORT file.name ASC
```
### [[Smallton Farms]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"Smallton Farms")
SORT file.name ASC
```
### [[Springvale]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"Springvale")
SORT file.name ASC
```
### [[Starfall Springs]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"Starfall Springs")
SORT file.name ASC
```
### [[The Capital]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"The Capital")
SORT file.name ASC
```
### [[The Village of Halflings and Kobolds]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"The Village of Halflings and Kobolds")
SORT file.name ASC
```

## NPC's by faction
### [[Gods]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"Gods")
SORT file.name ASC
```
### [[Knights of Reverence]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"Knights of Reverence")
SORT file.name ASC
```
### [[The Blinkertons]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"The Blinkertons")
SORT file.name ASC
```
### [[The Empire]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"The Empire")
SORT file.name ASC
```
### [[The Smalltons]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"The Smalltons")
SORT file.name ASC
```
### [[The Union]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"The Union")
SORT file.name ASC
```
### [[the winners]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"PC") or contains(type,"location") and contains(faction,"the winners")
SORT file.name ASC
```
### [[Warrior Champions]]
```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"Warrior Champions")
SORT file.name ASC
```