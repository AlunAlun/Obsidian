---
location: 
company:
title: 
email: 
aliases: 
---
tags:: [[👥 People MOC]]
# [[<% tp.file.title %>]]

## Notes
- 

## Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "V-CXO/Meetings" where contains(file.outlinks, [[]])
SORT file.cday DESC
```