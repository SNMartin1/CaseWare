# CaseWare
Notes and Resources on CaseWare

## From CaseWare Help:
 http://documentation.caseware.com

### Misc. Functions
http://documentation.caseware.com/2015/CaseView/en/Content/Calculations/Functions/Miscellaneous_Functions/Miscellaneous_Functions.htm?Highlight=functions

- ASSIGNEDTO
    - Syntax: ASSIGNEDTO("UserName")
    - Example: ASSIGNEDTO("Ted.Brimley")
          - This function will return true if Ted is assigned to the document.
    - Example: ASSIGNEDTO(WHOAMI(1))
          - This function will return true if the current user is assigned to the document.

- CELLCALC
    - Syntax: CELLCALC(<cell number>)
    - Example: CELLCALC(ABC.D3)
          - returns the cell calculation of cell ABC.D3
          - if cell ABC.D3 had a calculation of "GRP("1", "100," "BA")", it will return that

### About Cells
http://documentation.caseware.com/2015/CaseView/en/Content/Cells/About_cells.htm

### Table Property Commands
http://documentation.caseware.com/2015/CaseView/en/Content/Menus_and_commands/Table_Menu/Table_Properties_command_-_Table_menu.htm

## Videos

### Populating Data:
https://www.youtube.com/watch?v=wjp0UYYy4_U

### Editing the Mapping Database
https://www.youtube.com/watch?v=Mcllvn38po8
