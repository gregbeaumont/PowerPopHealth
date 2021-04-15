<b>FDA Data</b><br>
The files in this folder use Data from the FDA. <br>

<b>Sources</b><br>
Sources for these tables include: 
1. Food Recall Enforcement Reports - https://open.fda.gov/data/downloads/
2. CAERS Reports (Food Events) - https://open.fda.gov/data/downloads/ 

<b>Prerequisites</b><br>
1. Azure Data Factory (for ARM_FDA) - https://youtu.be/OIbfhVov3YY
2. Azure Data Lake (for ARM_FDA) - https://youtu.be/AS3OhGCQ8EQ 
3. Power BI Desktop or DataFlows (M code scripts)

<b>Deployment Instructions</b>
1. For the Azure <b>ARM_FDA</b> template file, copy the text and deploy it to Azure as shown in this video: https://youtu.be/Bg3zV_GIOJY .
2. In the <b>FDA CAERS</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows. Example for Power BI Desktop: https://youtu.be/EZXOQylIjVo . Example for Power BI DataFlows: https://youtu.be/_G2WniVVkMw .
3. Next deploy the <b>FDA Food Recalls</b> M code using the same method as #2 above.

<b>Relatable Data in Power Pop Health</b>
1. Food Recall Enforcement Reports
   - Date Scripts - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Date%20%26%20Time%20Scripts
2. CAERS Reports (Food Events)
   - Date Scripts - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Date%20%26%20Time%20Scripts 

<b>Notes</b><br>
 N/A

