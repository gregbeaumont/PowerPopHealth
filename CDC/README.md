<b>CDC Data</b><br>
The files in this folder use Data from the CDC. <br>

<b>Sources</b><br>
Sources for these tables include: 
1. Daily PM 2.5 Concentrations All Counties (Air Quality) - https://data.cdc.gov/Environmental-Health-Toxicology/Daily-PM2-5-Concentrations-All-County-2001-2016/7vdq-ztk9
2. Population Weighted Ultraviolet Irradiance - https://data.cdc.gov/Environmental-Health-Toxicology/Population-Weighted-Ultraviolet-Irradiance-2004-20/h28b-t43q 

<b>Prerequisites</b><br>
1. Azure Data Factory (for ARM_CDC) - https://youtu.be/OIbfhVov3YY
2. Azure Data Lake (for ARM_CDC) - https://youtu.be/AS3OhGCQ8EQ
3. Power BI Desktop or DataFlows (M code scripts)

<b>Deployment Instructions</b>
1. For the Azure <b>ARM_CDC</b> template file, copy the text and deploy it to Azure as shown in this video: https://youtu.be/Bg3zV_GIOJY .
2. In the <b>CDC PM 2.5 Concentrations All Counties</b> M code file, change "YOUR_DATA_LAKE" to the Account Name for your Azure Data Lake. Next, deploy the script to either Power BI Power Query or Power BI DataFlows. Example for Power BI Desktop: https://youtu.be/EZXOQylIjVo . Example for Power BI DataFlows: https://youtu.be/_G2WniVVkMw .
3. Next deploy the <b>CDC Population-Weighted-UV-Irradiance</b> M code to either Power BI Power Query or Power BI DataFlows using the same method as step #2 above. 

<b>Relatable Data in Power Pop Health</b>
1. CDC Daily PM2.5 Concentrations Air Quality
   - FIPS States and Counties - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Geography%20Data
   - Date Scripts - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Date%20%26%20Time%20Scripts
2. CDC Population Weighted Global Horizontal Irradiance
   - FIPS States and Counties - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Geography%20Data
   - Date Scripts - https://github.com/gregbeaumont/PowerPopHealth/tree/main/Date%20%26%20Time%20Scripts 

<b>Notes</b><br>
  Two County FIPS values are missing when connecting to the FCC FIPS States and Counties datasets, 08014 an 12086. 
