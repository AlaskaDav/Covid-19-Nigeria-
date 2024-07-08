# PROJECT TITLE 

## COVID 19 CASES NIGERIA

## Table of Content 

- [Description](#description)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [ETL Processing](#etl-processing)
- [Recommended Analysis](#recommended-analysis)
- [Data Analysis Procedures](#data-analysis-procedures)
- [Results and Findings](#results-and-findings)


### Project Description

 This is a record of Covid 19 cases from different states in Nigeria in 2019/2020, it contains 36 states in the year, obatined from NCDC website and compiled for government analysis. Each record represents the number of cases in each states, including the number affected areas, total case recorded, number of cases on admission, number of discharged and total number of death recorded in the states and entirely in the country.

 **NCDC**: The Nigeria Centre for Disease Control and Prevention (NCDC) was established in the year 2011 in response to the challenges of public health emergencies and to enhance Nigeria's preparedness and response to epidemics through prevention, detection and control of communicable diseases.

![Covid 19 Cases](https://github.com/AlaskaDav/Covid-19-Nigeria-/assets/155531290/469e2854-8785-4b58-867b-bf384571aeb6)

#### Data Source

Covid-19 Data : The data sets used for the analysis includes; 
- Covid-19.csv: This is a single set file containing the cases and records in each state of the country.

#### Tools Used 

- Power Querry: for data extraction from the website and transformation
    - [Download here](http://ncdc.gov.ng)
- Powerquerry: PowerQuerry was effective in carrying ETL processes on the data for data quality and organisation.
- PowerBI: For visualization and creating reports

#### ETL Processing

In the initial data preparation process, the following process was performed
1. Data Extraction: Extracting data files (.csv files) from NCDC website into Powerquerry for cleaning and transformation
  [Download here](
3. Transformation process taken place involves:
   - Promoted Header
   - Checked the column quality and column Profiling
   - Removed null Values from the data
   - Removing empty rows and columns
   - Changing data types
   - Creating new calculated column using DAX formula to calculate the total number of states affected.
4. Loading process involves loading the completely transformed and cleaned data into PowerBI to build dashboard for reporting and visualizations.
 
#### Recommended Analysis

1. Determine the total number of states affected by the pandemic. 
2. Determine the total number of cases confirmed and recorded in each states.
3. Determine the total number of death cases recorded and how many confirmed cases were successfully treated and discharged.
4. Determine the percentage of total population affected in the country.

#### Data Analysis Procedures:

- Collected data through .csv files from MsExcel.
- Uploading the data into PowerQuery for Cleaning and analysing the contents of the data
- Requested for data clarification and data validity.
- Loaded the data into PowerBi for visualization and Presentation.
- Providing insights, presenting informations and advice.
- Creating outstanding reports for end user understanding, board of directors and shareholders.

#### Results and Findings

The analysis results are summarized as follows;
1. The total number of states in Nigeria affected are 36 states and the total number of cases confirmed is **255,244**.
2. The total number of cases on admission is **2616**.
3. The total number of Deaths is **3142** and Discharged is **249,486**

#### Recommendations
Based on the analysis, I recommend the following actions that can help lower the rist of tranmission and contamination of the disease:
 - NCDC shoud encourage citizens to keep Wearing a mask and ensure enough distance is maintained.
 - When sneezing, citizens should ensure noses are covered with handkerchiefs.
 - Testing for COVID-19 can help you decide what to do next, and eliminatte any form of stigmatization in the hospitals which can cause poeple people from recieving treatment in due time.
 - Encourage people to receive treatment early inorder to reduce your risk of severe illness, aggravating health issues and taking steps to lower your chances of spreading COVID-19 to others.


 - Ensure the reliability of on-Time departure with good experience

#### Limitations

There was a difficulty in representing the insight from the data in periods, so, I had to create a Date table independently from the data and then built a relationship in the model table so as to present the report in a well organized periodic manner i.e Month reporting and Dayl)

