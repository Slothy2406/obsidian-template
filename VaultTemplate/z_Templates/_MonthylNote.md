---
date: <% tp.file.creation_date("YYYY-MM") %>
tags:
  - Monthly
---
<< [[<% tp.date.now("YYYY-MM", -1) %>]] | [[<% tp.date.now("YYYY-MM", 1) %>]] >>

# <% tp.file.title %>

<% tp.file.cursor() %>
