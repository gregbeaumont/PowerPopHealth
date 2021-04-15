<b>DRG MDC and Surgical Class Tables</b><br>
The files in this folder use Data from CMS. <br>

<b>Sources</b><br>
Sources for these tables include: 
1. MS DRGs v38.1 Appendix A- https://www.cms.gov/Medicare/Medicare-Fee-for-Service-Payment/AcuteInpatientPPS/MS-DRG-Classifications-and-Software
2. MDC and Surgical Class Hierarchy from Appendix D/E - https://www.cms.gov/Medicare/Medicare-Fee-for-Service-Payment/AcuteInpatientPPS/MS-DRG-Classifications-and-Software 

<b>Prerequisites</b><br>
1. Azure Data Factory (for ARM_DRG)
2. Azure Data Lake (for ARM_DRG)
3. Power BI Desktop or DataFlows (M code scripts)

<b>Deployment Instructions</b>
1. For the Azure <b>ARM_DRG</b> template file, copy the text and deploy it to Azure as shown in this video: https://youtu.be/Bg3zV_GIOJY .
2. In the <b>DRG to Surgical Class ETL</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows. Example for Power BI Desktop: https://youtu.be/EZXOQylIjVo . Example for Power BI DataFlows: https://youtu.be/_G2WniVVkMw .
3. Next deploy the <b>MDC and Surgical Class Hierarchy</b> M code to either Power BI Power Query or Power BI DataFlows using the same method as step #2 above.
4. Next deploy the <b>DRG MDC Surgical Class</b> M code to either Power BI Power Query or Power BI DataFlows using the same method as step #2 above. This Query references <b>DRG to Surgical Class ETL</b> and <b>MDC and Surgical Class Hierarchy</b>, so in Power BI DataFlows it requires a Premium Workspace.

<b>Relatable Data in Power Pop Health</b>
N/A 

<b>Notes</b><br>
These scripts are for DRG v38.1. Older versions of DRGs can be added by using the equivalent URLs in the ARM template for the older data sources.

