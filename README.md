
# Hospitality Domain - Power BI Project

### Problem Statement
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

## Data Processing and Preparation

#### Data Loading and Power Query Documentation 

- Connect with data sources (csv files)

- Then go to Tranform data to expand each and every dataset.

- Transformation in Power query

#### Connected relations

Power Query steps for tables:

- dim_date:
remove the column 'day_type'

 we are deleting this because, we got a feedback from the mock dashboard review that Friday and Saturday are considered as weekends in the industry and not sunday. But In our datasets, saturday and sunday are considered as weekends. So we delete this column and re-create day_type using calculated columns.

- dim_rooms
The column names are not captured here. We need to select "Use First Row as Headers" option

## DAX
Weeknum

New day_type (Calculated column)



## Dashboard
Key Measures



