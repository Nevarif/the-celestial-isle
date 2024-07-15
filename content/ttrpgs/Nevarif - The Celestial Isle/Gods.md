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
# [[Gods]]

```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"Gods")
SORT file.name ASC
```