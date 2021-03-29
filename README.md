## Intro to Power Pop Health ##
Power Pop Health is a collection of content intended to simplify the process of ingesting and prepping Healthcare Open Data for analytics, Business Intelligence, and more. Three basic factors contributed to the initial release:
1. Quite often I encounter teams eager to do analytics, but they need to get source data into an easy-to-use and scalable location.
2. Very few examples exist in the public domain for shaping and modeling Healthcare data for Business Intelligence and Analytics. Concepts such as efficient ETL/ELT, Data Modeling, and scalable enterprise data marts/warehouses often require extrapolating architectures from examples unrelated to Healthcare.
3. Over the last 5 years I have accumulated examples and tutorials for items 1-2. This first release is a repository to share those examples in a unified format, and in one place. Future additions to this repository will be based on feedback from the community, with an initial plan to focus primarily on Population Health data.

## What User Personas are the Target Audience? ##
1. Business Intelligence Professionals
2. Data Scientists
3. Business Analysts

## What types of Content are to be Expected in the Files? ##
All attempts will be made to make deployment of the content no code or low code. Documentation and content organization will focus on three type of content for specific audiences:
1. **Raw Data** - Primarily Azure ARM Templates designed to get Open Data into a Data Lake without making any transformations. The ARM Templates will be low code or no code whenever possible.
2. **Curated Data** - When source data requires significant transformations or cleanup to be usable, it will be labeled as Curated Data. This data will still be in raw form, but easier to use.
3. **Relational Data** - Relational Data will allow for queries amongst different tables, but it will not necessarily be optimized for Business Intelligence.
4. **Optimized Data** - Optimized Data will be cleaned, curated, transformed, and modeled to be ideal for efficient andf performant queries. Most of this content will be optimized for use with Power BI Power Query, DataFlows, and DataSets (Tabular Models).

## What do You Need to Use Power Pop Health Content? ##
Different technologies below may be needed for different components, depending on what you decide to deploy:
1. **An Azure subscription** - Note that some of the Power BI DataFlows / Power Query scripts can be redirected to other sources if you don't have an Azure subscription.
2. **Azure Data Lake Gen 2** - see below for depoloyment instructions
3. **Azure Data Factory** - see below for depoloyment instructions
4. **Azure SQL Database** - for specific data sets
5. **Azure Synapse** - for specific solutions
6. **Power BI** - DataFlows and/or Power Query, Power BI Desktop
7. **Power BI Premium** - only required for some of the DataFlows
