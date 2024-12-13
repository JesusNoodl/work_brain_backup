---
company:
department:
location:
title:
email:
aliases: []
---
tags: [[People MOC]]
<% await tp.file.move("/remote/People/" + tp.file.title)%>
# <% tp.file.title %>

# Notes
- 

# Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "Meeting Notes" where contains(file.outlinks, [[<% tp.file.title %>]])
SORT file.cday DESC
```