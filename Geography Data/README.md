<b>Geography Data</b><br>
The files in this folder are reference tables for common Geographical key values. <br>

<b>Sources</b><br>
Sources for these tables include: 
FCC FIPS list - https://transition.fcc.gov/oet/info/maps/census/fips/fips.txt 

<b>Prerequisites</b><br>
1. Azure Data Factory (for ARM_Geography) - https://youtu.be/OIbfhVov3YY
2. Azure Data Lake (for ARM_Geography) - https://youtu.be/AS3OhGCQ8EQ 
3. Power BI Desktop or DataFlows (M code scripts)

<b>Deployment Instructions</b>
1. 1. For the Azure <b>ARM_Geography</b> template file, copy the text and deploy it to Azure as shown in this video: https://youtu.be/Bg3zV_GIOJY .
2. In the <b>FIPS States</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows. Example for Power BI Desktop: https://youtu.be/EZXOQylIjVo . Example for Power BI DataFlows: https://youtu.be/_G2WniVVkMw .
3. Next deploy the <b>FIPS States & Counties</b> M code to either Power BI Power Query or Power BI DataFlows using the same method as step #2 above. This Query references <b>FIPS States</b>, so in Power BI DataFlows it requires a Premium Workspace.

<b>Relatable Data in Power Pop Health</b>
1. CDC Data - https://github.com/gregbeaumont/PowerPopHealth/tree/main/CDC 

<b>Notes</b><br>
  Two County FIPS values do not find matches when connecting to the FIPS States & Counties dataset, 08014 an 12086. 
