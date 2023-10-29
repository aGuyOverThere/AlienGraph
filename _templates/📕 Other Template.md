---
id: <% tp.file.title.split(" ")[0] %>
created_date: <% tp.file.creation_date('MM/DD/YYYY') %>
type: other
year: <% tp.file.creation_date('YYYY') %>
tags:
  - other
author: aGuyOverThere
---

----
<% await tp.file.move("📕 Other/" + "📕 " + tp.file.title) %>
