## NPC's in <% tp.file.title %> 

%% DATAVIEW_PUBLISHER: start
```dataview
table description as "Description" from "ttrpgs/<% tp.file.folder(false) %>"
WHERE contains(type,"NPC") or contains(type,"faction") and contains(location,"<% tp.file.title %>")
SORT file.name ASC
```
%%

| File | Description |
| ---- | ----------- |

%% DATAVIEW_PUBLISHER: end %%
