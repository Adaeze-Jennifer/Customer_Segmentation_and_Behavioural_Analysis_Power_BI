# 📊 Customer Segmentation and Behavioural Analysis Report (Power BI)
This project presents a customer segmentation and behavioural analysis conducted to better understand customer profiles and support data-driven marketing decisions. Using a dataset of 500 customers collected in 2025, the analysis explores demographics, regional distribution, tenure, income levels, and professional characteristics to generate actionable insights for retention and targeting strategies.

## 🔍Overview
The dataset contains 500 customer records spanning demographics, income, region, occupation, tenure, and segment classification. Data preparation was carried out in Power Query and included cleaning, transformation, and feature engineering. Three calculated columns (Year, Tenure, and Age Group) were created to support deeper analysis, alongside four DAX measures used for KPIs:
- Total Customers
- Average Age
- Average Tenure
- Average Income
A Power BI dashboard was developed with seven interactive visualisations across two report pages. Slicers were added for Region, Gender, Customer Segment, and Age Group to enable dynamic filtering and comparative analysis.

## 📌Objectives
- Analyse customer data and uncover patterns in demographics, income, tenure, and professional profiles
- Segment customers into meaningful groups for targeted marketing and retention strategies
- Evaluate customer growth trends over time using join date analysis
- Assess regional distribution and identify high-value customer locations
- Examine income and age patterns across different customer segments
- Build an interactive Power BI dashboard for dynamic exploration of customer data

## ❓Business Questions
- How has customer growth evolved over time?
- Which region has the highest number of customers?
- What are the dominant customer segments within the dataset?
- How are customers distributed across gender and age groups?
- Which age group has the highest average age profile?
- What is the average income and tenure of customers?
- What professional groups make up the largest portion of the customer base?
- Are there noticeable patterns between customer segment, income, and occupation?

## 📚Dataset Description
- **Source:** Customer Segmentation Dataset (2015–2025, 500 records)
- **Columns:** CustomerID, Name, Gender, Age, Region, Occupation, Income, Customer_Segment, Join_Date, Tenure, Age Group, 

## 🛠Tools & Technologies Used
- Microsoft Power BI (Power Query, DAX, Data Visualization)
- Microsoft Excel (Initial data inspection and validation)

## 🧹Data Cleaning (Power Query)
- Removed duplicate records
- Handled missing or inconsistent values
- Corrected data types (e.g., dates, numeric fields)
- Renamed and reordered columns for consistency

## 🔧 Data Transformation (Power Query)
- Year – Extracted from Join_Date
- Tenure – Calculated as number of years as a customer
- Age Group – Categorised into Youth, Young Adult, Adult, and Senior

## 📈Key Trends Discovered
### 1. Customer Profile (Age, Income, Tenure):
The average customer is 46.28 years old, with an average tenure of 4.96 years and an average income of $114,400. This defines a middle-aged, financially stable, and moderately long-tenured customer base, indicating a mature and established portfolio.

### 2. Gender Distribution:
The customer base is nearly balanced, with **51.2% **Male and **48.8%** Female, showing no significant gender bias and broad demographic coverage.

### 3. Customer Segment Distribution:
The Retail segment dominates **(57.2%),** followed by Corporate **(33.8%),** while Private customers represent only **9%.** This low Private share is consistent across all regions, suggesting a structural segmentation or positioning gap rather than a regional issue.

### 4. Customer Growth Trend:
Customer acquisition peaked around 2019–2020, followed by a consistent five-year decline through 2025, indicating a sustained acquisition challenge rather than a temporary fluctuation.

### 5. Regional Performance:
The South region leads in customer count, followed by East and North, while the West region consistently underperforms. However, segment distribution remains uniform across regions, confirming that the gap is driven by volume (acquisition) rather than customer type or fit.

### 6. Age Distribution:
Adults and Young Adults dominate the customer base, reinforcing that the business primarily serves mid-career professionals.

### 7. Occupational Behaviour vs Income:
Engineers represent the largest customer group by volume, while Traders record the highest average income. This indicates that income is not the primary driver of engagement, and suggests a stronger alignment between product usage and the professional context of Engineers rather than purchasing power alone.

## 📈 Trends and Behavioural Patterns
Customer acquisition **increased** steadily through the **mid-to-late 2010s,** **peaking** around **2019–2020,** before entering a **continuous five-year decline.** A single-year dip can reflect external disruption. However, a five-year downward trend indicates a structural acquisition challenge that requires deliberate intervention. While retention remains stable (supported by an average tenure of 4.96 years), weakening acquisition signals a structural issue in customer growth. 

Regional analysis confirms a **consistent hierarchy:** Regionally, South records the highest customer count, followed by East and North, with West trailing all three. Importantly, the segment distribution is **uniform** across regions, the variation is driven by acquisition efficiency rather than market fit.

Occupational analysis highlights a **behavioural divergence** between **income and engagement.** **Engineers** dominate **customer volume,** while **Traders,** despite having the **highest income levels,** account for fewer customers. This indicates that purchasing behaviour is more strongly influenced by occupational relevance than income alone.

## 📊 Dashboard Development (Project Requirements)
The following visualisations were developed in accordance with the project brief:
- Customer Growth Timeline
- Region with the Highest Customers
- Age Group with the Highest Average Age
- Professional Profile of Customers
- Customer Distribution Across Gender
- Customer Segment Distribution
Interactive slicers were implemented for Region, Gender, Customer Segment, and Age Group to enable dynamic filtering and deeper exploration of patterns across customer dimensions.

## ⭐ Exploratory Analysis (Beyond Project Requirements)
In addition to the required visualisations, an exploratory analysis of income distribution was conducted to further understand the financial profile of customers across occupational groups.

This extension was introduced independently to enhance behavioural interpretation of the dataset. The analysis revealed that income levels vary significantly across occupations, with Traders recording the highest average income despite lower customer volume compared to Engineers.

This finding reinforces the insight that customer engagement is not solely driven by income level, but is more closely associated with occupational context and product relevance.

## 💡Recommendations
- **Reassess Private Segment Strategy**
The Private segment remains consistently low at 9% across all regions, indicating a structural gap in positioning or product-market fit. A strategic review is required to determine whether this segment should be actively expanded or deprioritised.

- **Strengthen Retention of Engineer Segment**
Engineers represent the highest customer volume, indicating strong alignment between their professional context and the product offering. A targeted retention strategy should be implemented, including loyalty programs and behaviour-based engagement strategies.

- **Investigate Income–Engagement Misalignment in Traders**
Despite having the highest income levels, Traders account for fewer customers than Engineers. This suggests that engagement is driven more by occupational relevance than income, requiring further investigation into product fit and acquisition channels.

- **Address Declining Customer Acquisition**
Customer acquisition has declined steadily over five years despite stable retention. A structured diagnostic is required to identify breakdown points across region, occupation, and segment.

- **Improve Performance in West Region**
The West region consistently underperforms in customer volume despite having a similar segment distribution to other regions. This indicates an acquisition gap rather than a market mismatch.

- **Explore Premium Offering Opportunities**
With an average income of $114,400, there is clear potential for premium product offerings, particularly within underrepresented segments such as Private customers.

## Conclusion
This analysis provides a comprehensive understanding of customer structure, behaviour, and segmentation across 500 customers. The findings highlight a mature customer base, strong dependence on Retail and Corporate segments, and meaningful behavioural differences across occupations.

Key strategic concerns include declining customer acquisition, underperformance of the Private segment, and the divergence between income levels and engagement across occupations. Addressing these areas presents clear opportunities to improve targeting, retention, and long-term customer value.

## 📒Project Notebook 
- [View Power BI Project File (.pbix)](https://github.com/Adaeze-Jennifer/Customer_Segmentation_and_Behavioural_Analysis_Power_BI/blob/main/project%20files/customer_segmentation.pbix) – Contains the full Power BI report including data model, DAX measures, and interactive visualisations. _(Download and open in Power BI Desktop)._
- [Dashboard Preview](https://github.com/Adaeze-Jennifer/Customer_Segmentation_and_Behavioural_Analysis_Power_BI/blob/main/images/dashboard_screenshot.png) – Snapshot of the final interactive dashboard.
- [View Full Repository](https://github.com/Adaeze-Jennifer/Customer_Segmentation_and_Behavioural_Analysis_Power_BI/tree/main) – Full documentation, insights, and project breakdown.
- [Back to Top](#Customer_Segmentation_and_Behavioural_Analysis_Power_BI) - Project Overview and Documentation.
