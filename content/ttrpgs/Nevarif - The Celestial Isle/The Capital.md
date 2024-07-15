---
type: place
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
# [[The Capital]]

The capital city of [[The Empire]].

```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"The Capital")
SORT file.name ASC
```