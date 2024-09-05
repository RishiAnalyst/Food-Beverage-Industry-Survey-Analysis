# Food & Beverage Industry Survey Analysis with Power BI

## Project Overview
This project aims to analyze survey responses from the food and beverage industry to gain insights into consumer behavior, preferences, and perceptions. The analysis was conducted using Power BI, providing key trends, understanding brand perception, and identifying areas for improvement in product offerings and marketing strategies.

## Objective
The main objective of this project is to:
- Identify key consumer behavior trends.
- Understand consumer perception of various brands.
- Explore potential areas for product improvement.
- Provide actionable recommendations for enhancing marketing strategies.

## Data Source
The dataset used for this analysis contains survey responses from 10,000 individuals, including demographic information, consumption habits, brand perceptions, and preferences.

### Tables Used:
- Fact Table: fact_survey_responses
    - Response_ID: Unique identifier for each survey response.
    - Respondent_ID: Unique identifier for each respondent.
    - Consume_frequency, Consume_reason, Brand_perception, etc.
- Dimension Tables:
    - dim_respondents: Respondent_ID, Name, Age, Gender, City_ID.
    - dim_cities: City_ID, City, Tier.

## Data Cleaning
Data cleaning was performed using Power Query, with key steps including:
- Correcting spelling errors and standardizing values for consistency.
- Renaming columns for better visualization and understanding.
- Checking for null values and handling errors appropriately.

## Data Modeling
- The fact_survey_responses table was connected to the dim_respondents table using the Respondent_ID column.
- The dim_respondents table was connected to the dim_cities table using the City_ID column.

## New Measures Created
Five new measures were created for use in card visuals, including:
- Total Male Respondents
- Total Female Respondents
  % Male Respondents
- % Female Respondents
These measures were also included in tooltips for relevant visuals.

## Dashboard Overview
The dashboard consists of 17 visuals spread across 3 pages, including:
- Column Chart
- Stacked Bar Chart
- Pie Chart
- Donut Chart
- Treemap Chart
- Table
- Card Visuals

Additionally, navigation buttons and slicers were incorporated for improved interactivity and user experience.

## Key Insights
1. ### Demographics: 60.38% of respondents are male, with more than 50% in the 19-30 age group.
2. ### Consumption Patterns: Most respondents consume products 2-3 times a week, mainly for concentration during work/study and pre-exercise.
3. ### Brand Preference: Coca-Cola is the most preferred brand, while brand reputation is the primary factor for brand selection.
4. ### Health and Taste Preferences: Respondents prefer products with reduced sugar and more natural ingredients. The average taste rating is around 3.32 to 3.34.

## Recommendations
1. Enhance health perception by promoting natural ingredients and health benefits.
2. Improve taste quality and reduce sugar content to align with consumer preferences.
3. Increase brand visibility through targeted marketing campaigns, particularly in Tier 1 cities.
4. Optimize packaging by focusing on portable and innovative designs to attract younger consumers.

## Tools Used
- Power BI: For data visualization and dashboard creation.
- Power Query: For data cleaning and transformation.

## Project Files
- Power BI File (.pbix): Contains all data transformations, visuals, and analysis.
- Presentation File (.pptx): Summary of insights, key trends, and recommendations from the project.
- Explanation : Walkthrough of the analysis and insights.

## Conclusion
This project provided a comprehensive analysis of consumer behavior and preferences in the food and beverage industry, offering valuable insights for enhancing product offerings and marketing strategies. By leveraging data analytics tools such as Power BI, we were able to derive actionable recommendations to support decision-making processes.

