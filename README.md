[openrefine_recipe.json](https://github.com/user-attachments/files/30569086/openrefine_recipe.json)# eHA-Test-Assessment_Hikmat-
AI assistance (Claude, Anthropic) was used to plan the analytical approach, review SQL/QGIS logic, and structure documentation. All data cleaning decisions, thresholds, and analytical conclusions are my own judgment, made and defended in the constraint register / methodology notes below.
#Tool Stack
Data cleaning: OpenRefine
Spatial database: GeoPackage
Spatial analysis: QGIS
Form: XLSForm in Excel, validated with ODK Validate
#Folder Structure
/data-raw/        
   /data-cleaned/   
   /db/              
   /qgis/             
   /xlsform/         
   /docs/            
  #To reproduce: 
  open the raw file in OpenRefine, then Undo/Redo → Apply → select this /data-cleaned/[Upload[
  {
    "op": "core/fill-down",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "NATIONAL ADMINISTRATIVE REFERENCE  ///  LGA TO SENATORIAL DISTRICT MAPPING (2024 revision)",
    "description": "Fill down cells in column NATIONAL ADMINISTRATIVE REFERENCE  ///  LGA TO SENATORIAL DISTRICT MAPPING (2024 revision)"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "Column 2",
    "expression": "value",
    "edits": [
      {
        "from": [
          "Daibewo",
          "Daibewo  "
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "Daibewo"
      },
      {
        "from": [
          "TIVSANO-NORTH",
          "Tivsano-North"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "Tivsano-North"
      }
    ],
    "description": "Mass edit cells in column Column 2"
  },
  {
    "op": "core/fill-down",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "Column 3",
    "description": "Fill down cells in column Column 3"
  },
  {
    "op": "core/fill-down",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "Column 3",
    "description": "Fill down cells in column Column 3"
  },
  {
    "op": "core/fill-down",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "Column 3",
    "description": "Fill down cells in column Column 3"
  },
  {
    "op": "core/fill-down",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "Column 3",
    "description": "Fill down cells in column Column 3"
  },
  {
    "op": "core/fill-down",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "Column 3",
    "description": "Fill down cells in column Column 3"
  },
  {
    "op": "core/fill-down",
    "engineConfig": {
      "facets": [],
      "mode": "record-based"
    },
    "columnName": "Column 3",
    "description": "Fill down cells in column Column 3"
  }
]ing openrefine_recipe.json…]() file.
  #Reconciliation log: 
[name_reconciliation_log.csv](https://github.com/user-attachments/files/30569093/name_reconciliation_log.csv)
raw_name,matched_name,status(matched/unmatched)


