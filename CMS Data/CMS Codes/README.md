
<b>CMS Codes</b><br>
The files in this folder use Standard Codes Data from CMS. <br>

<b>Sources</b><br>
Sources for these tables include: 
CMS ICD10 CM 2021 - https://www.cms.gov/medicare/icd-10/2021-icd-10-cm 
CMS ICD10 PCS 2021 - https://www.cms.gov/medicare/icd-10/2021-icd-10-pcs 

<b>Deployment Instructions</b>
1. Files are in the respective folders, separated in order to provide clutter.
2. In the <b>ARM_CMS_ICD10_Codes</b> file from the ICD10 folder, change "YOUR_DATA_LAKE" to the name of your Azure Data Lake. Deploy Azure ARM Template.
3. In the <b>ARM_CMS_DRG_MDC_Codes</b> file from the DRG MDC Surgical Class folder, change "YOUR_DATA_LAKE" to the name of your Azure Data Lake. Deploy Azure ARM Template.
4. Deploy the <b>FIPS States</b> M code to either Power BI Power Query or Power BI DataFlows.
5. Next deploy the <b>FIPS States & Counties</b> M code to either Power BI Power Query or Power BI DataFlows. Note that this script references <b>FIPS States</b> so they need to be deployed in sequence. In DataFlows these scripts will require a Power BI Premium Workspace.

<b>Relatable Data in Power Pop Health</b>
1. CDC Daily PM2.5 Concentrations Air Quality - 
2. CDC Population Weighted Global Horizontal Irradiance - 

<b>Notes</b><br>
  Two County FIPS values are missing when connecting to the CDC datasets, 08014 an 12086. 
