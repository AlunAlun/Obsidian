[[+Home]] %% tags:: #MOC %% 

**Template:** [[Template, Companies]]

```meta-bind-button
label: New Company
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
    templateFile: V-CXO/➕Extras/Templates/Template, Companies.md
    folderPath: V-CXO/Companies
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```
```dataview
TABLE website AS "Website"
FROM "V-CXO/Companies" and -#MOC
SORT file.cday DESC
```
