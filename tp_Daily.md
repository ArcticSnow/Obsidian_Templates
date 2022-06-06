Tags: #daily_note  
# <% tp.file.creation_date("MMMM D") %> Notes 
<< [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>|<% tp.date.now("YYYY-MM-DD, dddd", -1, tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>|<% tp.date.now("YYYY-MM-DD, dddd", 1, tp.file.title, "YYYY-MM-DD") %>]]>>
```mermaid
gantt
    dateFormat  HH-mm
    axisFormat %H:%M
    section Tasks
    Emails/Planning :09-45, 60mm
	Break      :10-45, 15mm
	Writing    :11-00, 90mm
	Lunch      :12-30, 60mm
    Processing :13-30, 90mm
    Coffee     :15-00, 15mm
    Processing    :15-15, 60mm
    Review notes :16-30, 30mm
    End        :17-00, 0mm
```

## Objective for today
- <% tp.file.cursor(1) %>


---
Created on <% tp.file.creation_date("MMM DD, YYYY") %> by S. Filhol
Last modified on <% tp.file.last_modified_date("MMM DD, YYYY") %>



 
