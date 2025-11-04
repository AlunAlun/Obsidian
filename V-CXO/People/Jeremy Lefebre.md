---
location: Berlin
company: "[[Slow Lettuce]]"
title: CEO
email: jeremy@slowlettuce.io
aliases:
---
tags:: [[👥 People MOC]]
## Notes
- 

## Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "V-CXO/Meetings" where contains(file.outlinks, [[]])
SORT file.cday DESC
```