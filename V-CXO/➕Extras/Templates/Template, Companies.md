---
location:
website: 
aliases: 
---
tags:: [[📈 Companies MOC]]
# [[<% tp.file.title %>]]

## Notes
- 

## People
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "V-CXO/People" where contains(file.outlinks, [[]])
SORT file.cday DESC
```

## Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "V-CXO/Meetings" where contains(file.outlinks, [[]])
SORT file.cday DESC
```