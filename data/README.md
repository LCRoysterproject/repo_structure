This is the `data` folder structure outline. The `data` folder will include all data relevant to this specific repository project. This folder will include a **master dataset** used for project analysis, and will preferably be a single data file in two formats (.csv, .xslx). This file can be named "data.csv". This **master dataset** does not need additional naming parameters, unless it is subsetted.  

## Naming Standards  
Every dataset file is required to be in lowercase, no uppercase (camelcase) nor all caps, all names with separate words need to include a underscore ( _ ), no dates in the names unless it helps with the descriptions of the content (i.e., discharge_1941_2018.csv, landings_1986_2018.txt).  

Mandatory folders in `data` are:  
- archive  
  
 The `archive` folder consists of any raw datasets used to update the repository master dataset. 

Allowable optional folders in `data` could be:  
- water  
- heights  
- counts 
- transect  
- shell_biomass 
  
It is recommended only to add additional folders if there are more than 10 different datasets (this is **NOT** normal for one individual repository project). 
