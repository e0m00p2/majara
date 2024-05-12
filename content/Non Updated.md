```dataview
LIST rows.file.name
WHERE !Status
SORT file.name ASC
GROUP BY file.folder
```
