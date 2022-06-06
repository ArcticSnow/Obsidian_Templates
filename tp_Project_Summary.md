---
project: <% tp.file.cursor(1) %>
---

# Project `$=dv.span(dv.current().project)` Summary

## Project Meeting Review
```dataview
list from #template and #meeting
sort file.ctime DESCENDING
```

## All notes mentioning the project
```dataview
list from #template 
sort file.ctime DESCENDING
```
---
#projectsummary Created on <% tp.file.creation_date("MMM DD, YYYY") %> by S. Filhol

