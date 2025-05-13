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
# All Meetings

```dataview
TABLE file.cday as Created, type, company, summary
FROM "V-CXO/Meetings" and -#MOC
SORT file.cday DESC
```