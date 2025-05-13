---
location: Swansea
company: Bob Co
title: CEO
email: Bob@bob.com
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