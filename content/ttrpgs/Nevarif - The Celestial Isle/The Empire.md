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
# [[The Empire]]

Nevarif was once a nation of free towns and villages. While this allowed for many freedoms, it also allowed for much chaos. To try and bring order and safety to Nevarif, The Empire was established by [[Emperor New Name]].

```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"The Empire")
SORT file.name ASC
```