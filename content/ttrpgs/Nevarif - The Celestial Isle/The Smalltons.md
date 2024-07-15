---
type: faction
faction: 
location: 
world: Nevarif - The Celestial Isle
campaign: Nevarif - The Celestial Isle
date: 2024-07-14
description: ""
race: 
gender: 
class:
---
# [[The Smalltons]]

Family owned business powerhouse headed by [[Ma Smallton]]. Consists of [[Ma Smallton]], [[Pa Smallton]], and [[Dalton Smallton]]

```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"The Smalltons")
SORT file.name ASC
```