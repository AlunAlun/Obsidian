[[+Home]] 
%% tags:: #MOC %%

**Template:** [[Template, People]]

```meta-bind-button
label: New Person
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
    templateFile: V-CXO/➕Extras/Templates/Template, People.md
    folderPath: V-CXO/People
    fileName: New Person
    openNote: true
    openIfAlreadyExists: false
``` 
```dataview
table company AS "Company", title AS "Title", email
from "V-CXO/People" and -#MOC
sort file.name asc
```