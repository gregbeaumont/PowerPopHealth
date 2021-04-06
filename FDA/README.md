<b>FDA Data</b><br>
The files in this folder use Data from the FDA. <br>

<b>Sources</b><br>
Sources for these tables include: 
1. Food Recall Enforcement Reports - https://open.fda.gov/data/downloads/
2. CAERS Reports (Food Events) - https://open.fda.gov/data/downloads/ 

<b>Deployment Instructions</b>
1. In the Azure <b>ARM_FDA</b> template file, change "YOURDATALAKE" to the Account Name of your Azure Data Lake. Details here: https://docs.microsoft.com/en-us/power-query/connectors/datalakestorage . Deploy Azure ARM Template.
2. In the <b>FDA CAERS</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows.
3. Next deploy the <b>FDA Food Recalls</b> M code to either Power BI Power Query or Power BI DataFlows using the same method as step #2 above. 

<b>Relatable Data in Power Pop Health</b>
1. Food Recall Enforcement Reports
   - Date Scripts - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Date%20%26%20Time%20Scripts
2. CAERS Reports (Food Events)
   - Date Scripts - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Date%20%26%20Time%20Scripts 

<b>Notes</b><br>
 N/A

