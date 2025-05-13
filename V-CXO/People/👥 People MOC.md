[[+Home]] 
tags:: #MOC

**Template:** [[Template, People]]

```meta-bind-button
label: New Person D
icon: ""
style: default
class: "green-button desktop-only"
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
```meta-bind-button
label: New Person M
icon: ""
style: default
class: "green-button ios-only"
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: templaterCreateNote
    templateFile: ➕Extras/Templates/Template, People.md
    folderPath: People
    fileName: New Person
    openNote: true
    openIfAlreadyExists: false
```
# People
```dataview
table title
where file.folder = "V-CXO/People" or file.folder = "People"
and !contains(tags, "#MOC")
sort file.name asc
```


bob
```dataview
table file.name, tags
where contains(file.folder, "V-CXO/People")

```