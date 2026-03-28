<%*
const title = tp.file.title
const date = tp.date.now("YYYY-MM-DD")
await tp.file.rename(`${date}-${title}`)
%>

---
title: "<% tp.file.title %>"
date: <% tp.date.now("YYYY-MM-DD") %>
categories: [AI-Engineering]
tags: [Paper]
---