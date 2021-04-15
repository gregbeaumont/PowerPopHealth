<b>DRG MDC and Surgical Class Tables</b><br>
The files in this folder use Data from CMS. <br>

<b>Sources</b><br>
Sources for these tables include: 
1. MS DRGs v38.1 Appendix A- https://www.cms.gov/Medicare/Medicare-Fee-for-Service-Payment/AcuteInpatientPPS/MS-DRG-Classifications-and-Software
2. MDC and Surgical Class Hierarchy from Appendix D/E - https://www.cms.gov/Medicare/Medicare-Fee-for-Service-Payment/AcuteInpatientPPS/MS-DRG-Classifications-and-Software 

<b>Deployment Instructions</b>
1. In the Azure <b>ARM_DRG</b> template file, change "YOURDATALAKE" to the Account Name of your Azure Data Lake. Details here: https://docs.microsoft.com/en-us/power-query/connectors/datalakestorage . Deploy Azure ARM Template.
2. In the <b>FIPS States</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows.
3. Next deploy the <b>FIPS States & Counties</b> M code to either Power BI Power Query or Power BI DataFlows using the same method as step #2 above. Note that this script references <b>FIPS States</b> so they need to be deployed in sequence. In DataFlows these scripts will require a Power BI Premium Workspace.

<b>Relatable Data in Power Pop Health</b>
1. CDC Daily PM2.5 Concentrations Air Quality - 
2. CDC Population Weighted Global Horizontal Irradiance - 

<b>Notes</b><br>

