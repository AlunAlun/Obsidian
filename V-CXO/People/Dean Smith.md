---
location: Cabrils
company: "[[Assuring Business]]"
title: CEO
email: dean@assuringbusiness.com
aliases:
---
tags:: [[👥 People MOC]]
## Notes
- 

## Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "Timestamps/Meetings" where contains(file.outlinks, [[]])
SORT file.cday DESC
```