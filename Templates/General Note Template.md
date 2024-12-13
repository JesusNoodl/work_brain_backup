---
dateTime: <% tp.file.creation_date() %>
type: meeting
company: 
summary: " "
---
tags: [[General MOC]]
Date: [[<% tp.date.now("YYYY-MM-DD-dddd") %>]]
<% await tp.file.move("/remote/General Notes/" + tp.date.now("YYYY-MM-DD") + " " + tp.file.title) %>
# [[<% tp.date.now("YYYY-MM-DD") + " " + tp.file.title %>]]

