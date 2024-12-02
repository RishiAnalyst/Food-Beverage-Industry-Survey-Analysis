# Food & Beverage Industry Survey Analysis with Power BI

### Project Live Report: https://app.powerbi.com/view?r=eyJrIjoiZTA2MWRiNjQtMzcwNy00YTMzLWE4YTItODAxN2UyODM1MThhIiwidCI6IjlmMzA5MDY2LTU1Y2YtNDQ4NS04N2Q0LWViNTljZDdiYzY4NCJ9

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


## 📊 Insights

### **Page 1: Overview of Respondent Demographics and Preferences**

![Screenshot (237)](https://github.com/user-attachments/assets/025fcd6c-49c9-41b2-90f3-374b102242bc)

- **Total Respondents**:  
  - **10,000 participants** in the survey.  
  - **Male respondents**: **60.38% (6,038)**.  
  - **Female respondents**: **34.55% (3,455)**.  
  - **Non-binary respondents**: **5%**, an underexplored group for inclusivity.

- **General Perception of Food & Beverage Products**:  
  - **Effective (2.9K respondents)** – Trust in the product's benefits.  
  - **Healthy & Dangerous (2.2K each)** – Polarized views regarding health and safety.  

- **Price Distribution**:  
  - **₹50-99**: **4.3K respondents** prefer products in this affordable range.  
  - **₹150+**: Smaller group, indicating a **niche market** for premium products.

- **Age Distribution**:  
  - **55% of respondents** are in the **19-30 age group**, signaling a younger audience.  
  - **Older demographics (46+ years)** show **lower participation**, suggesting a targeted approach might increase engagement.

- **City-Wise Distribution**:  
  - **Top cities**: Bangalore (2.8K), Hyderabad (1.8K), and Mumbai (1.5K).  
  - **Potential growth**: Engage cities like Ahmedabad and Jaipur, which have minimal respondents.

---

### **Page 2: Brand Perceptions, Awareness, and Preferences**


![Screenshot (239)](https://github.com/user-attachments/assets/ded5d462-78b9-47e4-8be2-fa6bd81da18c)


- **Current Brands and Perception**:  
  - **Coca-Cola**: Most popular with **2.54K positive sentiments**.  
  - **Pepsi**: Following Coca-Cola with **2.11K positive sentiments**.  
  - **Smaller brands (Blue Bull, Sky 9)**: Neutral or negative reception, indicating a need for better positioning.

- **Brand Awareness**:  
  - **Coca-Cola & Pepsi**: Widely recognized by **1.1K+ respondents**.  
  - **Emerging brands (e.g., CodeX)**: Lower visibility, suggesting potential for growth through marketing.

- **Reasons for Choosing Brands**:  
  - **Brand reputation**: Key driver for **2.7K respondents**.  
  - **Taste/flavor preferences & availability**: Other significant factors.

- **Packaging Preferences**:  
  - **Portable cans** (39.84%) and **innovative designs** (30.47%) dominate.  
  - **Eco-friendly packaging**: Limited preference (9.83%), but room for improvement.

- **Limited Edition Packaging**:  
  - **39.46%** interested in limited edition packaging.  
  - **20.31% unsure**, signaling an opportunity to educate consumers on exclusivity.

- **Desired Product Improvements**:  
  - **Reduced sugar content**: **3K respondents**.  
  - **More natural ingredients**: **2.5K respondents**.  
  - **Wider product range**: **2.04K respondents**.

---

### **Page 3: Product Consumption Patterns**

![Screenshot (238)](https://github.com/user-attachments/assets/74468faa-774b-4fce-bab7-7f115d177a1c)


- **Product Consumption Frequency**:  
  - **Most common**: **2-3 times a week (3.4K respondents)** – Moderate but consistent consumption.  
  - **Least popular**: **Daily (1.35K respondents)** and **Once a week (1.6K respondents)** – Daily consumption is less common.

- **Primary Reasons for Consumption**:  
  - **Energy and focus**: **3.6K respondents** use products primarily for energy.  
  - **Performance boost**: Less significant, indicating a niche need.

- **Consumption Situations**:  
  - **Sports/Exercise**: **4.5K respondents** – Strong association with physical activity.  
  - **Driving/Commuting**: Less popular, suggesting **a potential mismatch** in consumption situations.

- **Purchase Location**:  
  - **Supermarkets**: **40.2%** of respondents prefer supermarkets for purchasing.  
  - **Online retailers**: **25%**, showing the **growth** of online sales.  
  - **Local stores**: Least common, indicating **limited engagement** in smaller shops.

- **Marketing Channels**:  
  - **Online ads**: **40.2%** of respondents are influenced by digital marketing.  
  - **TV commercials**: **26%** still effective, though secondary to online.  
  - **Print media**: Least effective (**8.4%**), suggesting reduced relevance.

---

## 📌 Key Takeaways
1. **Consumer Base**:  
   - The majority of respondents are young adults (19-30 years), with a significant portion of the audience being male.  
   - There's an opportunity to engage **older demographics** (46+ years) more effectively.

2. **Brand Perception and Loyalty**:  
   - Established brands like Coca-Cola and Pepsi dominate, but there’s room for emerging brands to grow through **targeted marketing**.  
   - **Brand reputation** and **taste** are key drivers for consumer purchases.

3. **Product Preferences**:  
   - Consumers favor **affordable price ranges (₹50-99)**, but there's also a niche market for **premium products (₹150+)**.  
   - There's a clear demand for **healthier options**, such as products with **reduced sugar** and **natural ingredients**.

4. **Consumption Habits**:  
   - Most consumers consume products **2-3 times a week**, primarily for **energy and focus**.  
   - The primary consumption situation is **sports/exercise**, indicating a **health-conscious** target market.

5. **Purchase Behavior**:  
   - **Supermarkets** remain the leading sales channel, but **e-commerce** is a growing segment.  
   - Traditional media (TV and print) still play a role, though **online ads** dominate.

---

## 🎯 Recommendations

### **1. Targeted Marketing Strategies**
- **#FocusOnYouth**: Emphasize digital marketing efforts for the **19-30 age group**, leveraging **online ads** and **social media** campaigns.  
- **#ExpandToOlderDemographics**: Design campaigns that specifically appeal to **46+ years** consumers to broaden your target market.

### **2. Product Innovations**
- **#HealthConsciousProducts**: Introduce product variants with **reduced sugar** and **natural ingredients** to meet the demands of health-conscious consumers.  
- **#DiversifyProductRange**: Expand product offerings to cater to different consumer preferences, from **affordable options** to **premium choices** (₹150+).

### **3. Brand Positioning and Awareness**
- **#LeverageBrandReputation**: For new or emerging brands like CodeX, focus on building strong **brand reputation** through **trust-building campaigns**.  
- **#InnovativePackaging**: Emphasize **portable cans** and **eco-friendly designs** to appeal to convenience-driven and environmentally conscious consumers.

### **4. Distribution and Retail Strategy**
- **#MaximizeSupermarketPresence**: Ensure strong visibility in **supermarkets** as the primary purchase location.  
- **#BoostEcommercePresence**: Invest in online retail platforms to tap into the growing e-commerce segment (25% of respondents).

### **5. Marketing and Advertising**
- **#DigitalDominance**: Focus on **online ads** for maximum engagement, especially with younger consumers.  
- **#TVAdsForBroadReach**: Continue using TV commercials for broader reach, particularly for middle-aged and older demographics.  
- **#ReassessPrint**: Consider reducing reliance on **print media** as it shows minimal effectiveness in driving consumer decisions.

---

## 🔑 Key Metrics
- **Demographics**: Male, young adults (25-34), and middle-income consumers dominate.  
- **Brand Loyalty**: Taste and pricing are key loyalty drivers.  
- **Consumption Habits**: Most consumers prefer 2-3 times a week, with energy and focus as primary reasons.  
- **Situational Use**: Sports/Exercise is the most common use case.  
- **Purchase Channels**: Supermarkets lead, but online retail is growing rapidly.  
- **Marketing Effectiveness**: Online ads outperform traditional methods like TV and print.  

## Tools Used
- Power BI: For data visualization and dashboard creation.
- Power Query: For data cleaning and transformation.

## Project Files
- Power BI File (.pbix): Contains all data transformations, visuals, and analysis.
- Presentation File (.pptx): Summary of insights, key trends, and recommendations from the project.
- Explanation : Walkthrough of the analysis and insights.

## Conclusion
This project provided a comprehensive analysis of consumer behavior and preferences in the food and beverage industry, offering valuable insights for enhancing product offerings and marketing strategies. By leveraging data analytics tools such as Power BI, we were able to derive actionable recommendations to support decision-making processes.

