# eHA-Test-Assessment_Hikmat-
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
  open the raw file in OpenRefine, then Undo/Redo → Apply → select this /data-cleaned/openrefine_recipe.json file.
