[[+Home]] %% tags:: #MOC %% 

**Template:** [[Template, Meeting]]

```meta-bind-button
label: New Meeting
icon: ""
style: default
class: "green-button"
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: templaterCreateNote
    templateFile: V-CXO/➕Extras/Templates/Template, Meeting Note.md
    folderPath: V-CXO/Meetings
    fileName: Meeting
    openNote: true
    openIfAlreadyExists: false
```
```dataview
TABLE file.cday as "Date", type AS "Type", company AS "Company", summary AS "Summary"
FROM "V-CXO/Meetings" and -#MOC
SORT file.cday DESC
```