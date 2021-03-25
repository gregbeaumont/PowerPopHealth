<b>Geography Data</b><br>
The files in this folder are reference tables for common Geographical key values. <br>

<b>Sources</b><br>
Sources for these tables include: 
FCC FIPS list - https://transition.fcc.gov/oet/info/maps/census/fips/fips.txt 

<b>Deployment Instructions</b>
1. In the <b>ARM_Geography</b> file, change "YOUR_DATA_LAKE" to the name of your Azure Data Lake. Deploy Azure ARM Template.
2. Deploy the <b>FIPS States</b> M code to either Power BI Power Query or Power BI DataFlows.
3. Next deploy the <b>FIPS States & Counties</b> M code to either Power BI Power Query or Power BI DataFlows. Note that this script references <b>FIPS States</b> so they need to be deployed in sequence. In DataFlows these scripts will require a Power BI Premium Workspace.

<b>Relatable Data in Power Pop Health</b>
1. CDC Daily PM2.5 Concentrations Air Quality - 
2. CDC Population Weighted Global Horizontal Irradiance - 

<b>Notes</>
  Two County FIPS values are missing when connecting to the CDC datasets, 08014 an 12086. 
