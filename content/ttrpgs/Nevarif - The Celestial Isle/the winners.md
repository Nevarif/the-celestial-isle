---
type: faction
faction: 
location: 
world: Nevarif - The Celestial Isle
campaign: Nevarif - The Celestial Isle
date: 2024-07-14
description: our heroes
race: 
gender: 
class:
---
# [[the winners]]

[[Bebe]], [[Lariel]], [[Glacier]], and [[Astra]]

```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"the winners")
SORT file.name ASC
```