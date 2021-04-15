<b>ICD10 Tables</b><br>
The files in this folder use Data from CMS. <br>

<b>Sources</b><br>
Sources for these tables include: 
1. 2021 ICD10 CM tables - https://www.cms.gov/medicare/icd-10/2021-icd-10-cm
2. 2021 ICD10 PCS tables - https://www.cms.gov/medicare/icd-10/2021-icd-10-pcs 

<b>Prerequisites</b><br>
1. Azure Data Factory (for ARM_CMS_ICD10_Codes) - https://youtu.be/OIbfhVov3YY
2. Azure Data Lake (for ARM_CMS_ICD10_Codes) - https://youtu.be/AS3OhGCQ8EQ 
3. Power BI Desktop or DataFlows (M code scripts)

<b>Deployment Instructions</b>
1. For the Azure <b>ARM_CMS_ICD10_Codes</b> template file, copy the text and deploy it to Azure as shown in this video: https://youtu.be/Bg3zV_GIOJY .
2. In the <b>ICD10 CM</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows. Example for Power BI Desktop: https://youtu.be/EZXOQylIjVo . Example for Power BI DataFlows: https://youtu.be/_G2WniVVkMw .
3. In the <b>ICD10 PCS</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows. Example for Power BI Desktop: https://youtu.be/EZXOQylIjVo . Example for Power BI DataFlows: https://youtu.be/_G2WniVVkMw .


<b>Relatable Data in Power Pop Health</b>
N/A 

<b>Notes</b><br>
These scripts are for ICD10 version 2021. Older versions of ICD10s can be added by using the equivalent URLs in the ARM template for the older data sources.


