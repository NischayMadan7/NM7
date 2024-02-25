
# Road Accident - Excel Project
### 1. Requirement  gathering from client

Clients wants to create a Road Accident Dashboard for year 2021 and 2022 so that they can have insight on the below requirements-

- Primary KPI - Total Casualties taken place after the accident

- Primary KPI's - Total Casualties & percentage of total with respect to accident severity and maximum casualties by type of vehicle

- Secondary KPI's - Total Casualties with respect to vehicle type

- Monthly trend showing comparison of casualties for Current Year and Previous Year
- Maximum casualties by Road Type

- Distribution of total casualties by Road Surface

- Relation between Casualties by Area/ Location & by Day/Night

### 2. STAKEHOLDERS 
- Ministry of Transport 
- Road Transport Department
- Police Force
- Emergency Services Department
- Road Safety Corps
- Transport Operators
- Traffic Management Agencies
- Public
- Media

### 3. Data cleaning
- Column size adjustment and Add Filter

- Accident_index column is unique key 

- Checking for Missing and Duplicate values

    We do have some missing values in the Road_Type  amd Road_Surface_Conditions Column but they are even less than 0.5% of the values so it wont affect our analysis and it is acceptable to ignore them 

- Checking for Typos and fixing it with FIND and REPLACE method

    Changing fetal (49 values) to fatal in Accident_severity and Changing Auto traffic sigl (92 values) to Auto traffic signal in Junction_control 

### 4. Data Processing 
 We want to show monthy trendline so we will add a month column (=TEXT(value,"mmm") and for year =TEXT(value,"yyyy") 
 
### 5. Data Analysis by Pivot Tables and Excel Functions
#### Pivot Tables 

- Sum of No. of casualties 

- No. of casualties with respect to Accident_severity and from that making Table for Fatal severity (KPI) - making a donut chart Doing the same for Serious and Slight severity

- No. of casualties with respect to Vehicle_type   
    Merging the various vehicle types into few major categories 

- No. of casualties with respect to Month and with a Year Filter 
- No. of casualties with respect to Road_Type           
    Also formating values to thousands("K")
- No. of casualties with respect to Road_Surface_Conditions. We will merge the various Road Surface types into 2 major categories
- No. of casualties with respect to Location/Area
- No. of casualties with respect to Light Conditions    
    Merging the various types into few major categories 

### 6. Dashboard
- Now making a Report by displaying all the charts and numbers analysed from the pivot tables 
- To further interact with the data and get more insights 
    Adding Filter Panel with Accident Date Timeline and Area Slicer     
    Adding Panel with Hyperlink 

