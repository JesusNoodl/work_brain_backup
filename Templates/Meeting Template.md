---
dateTime: <% tp.file.creation_date() %>
type: meeting
company: 
summary: " "
---
tags: [[Meetings MOC]]
Date: [[<% tp.date.now("YYYY-MM-DD-dddd") %>]]
<% await tp.file.move("/remote/Meeting Notes/" + tp.date.now("YYYY-MM-DD") + " " + tp.file.title) %>
# [[<% tp.date.now("YYYY-MM-DD") + " " + tp.file.title %>]]

**Attendees**: 


## Agenda/Questions
1. 

## Notes


## Actions
