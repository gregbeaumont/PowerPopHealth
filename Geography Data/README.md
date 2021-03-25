<b>Geography Data</b><br>
The files in this folder are reference tables for common Geographical key values. <br>

<b>Sources</b><br>
Sources for these tables include: 
FCC FIPS list - https://transition.fcc.gov/oet/info/maps/census/fips/fips.txt 

<b>Deployment Instructions</b>
1. In the <b>ARM_CDC</b> file, change "YOUR_DATA_LAKE" to the name of your Azure Data Lake. Deploy Azure ARM Template.
2. The <b>CDC Daily PM2.5 Concentrations Air Quality</b> and <b>CDC Population Weighted UV Irradiance</b> can be deployed to either Power BI Power Query or Power BI DataFlows together or separately.

<b>Relatable Data in Power Pop Health</b>
1. FIPS States & Counties - https://github.com/gregbeaumont/PowerPopHealth/blob/main/Geography%20Data/FIPS%20States%20%26%20Counties
2. Date Table - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Date%20%26%20Time%20Scripts 

<b>Notes</b><br>
  Two County FIPS values do not find matches when connecting to the FIPS States & Counties dataset, 08014 an 12086. 
