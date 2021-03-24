<b>Geography Data</b><br>
The files in this folder are reference tables for common Geographical key values. <br>

<b>Sources</b><br>
Sources for these tables include: 
FCC FIPS list - https://transition.fcc.gov/oet/info/maps/census/fips/fips.txt 

<b>Deployment Instructions</b><br>
1. Deploy Azure ARM Template. Replace "YOUR_DATA_LAKE" and "YOUR_DATA_LAKE_FOLDER" with the corresponding values for your Azure Data Lake (ADLSv2).
2. Deploy the <b>FIPS States</b> M code to either Power BI Power Query or Power BI DataFlows.
3. Next deploy the <b>FIPS States & Counties</b> M code to either Power BI Power Query or Power BI DataFlows. Note that this script references <b>FIPS States</b> so they need to be deployed in sequence. In DataFlows these scripts will require a Power BI Premium Workspace.

