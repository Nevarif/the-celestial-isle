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
# [[Knights of Reverence]]

The faction of local and regional knights that take up jobs to support [[The Empire]] and its' subjects.

```dataview
table description as "Description" from "ttrpgs/Nevarif - The Celestial Isle"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"Knights of Reverence")
SORT file.name ASC
```