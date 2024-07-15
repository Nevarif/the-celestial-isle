```dataview
table description as "Description" from "ttrpgs/<% tp.file.folder(false) %>"
WHERE contains(type,"NPC") or contains(type,"location") and contains(faction,"<% tp.file.title %>")
SORT file.name ASC
```