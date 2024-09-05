# 📊 Home Loan Dashboard - Power BI

## 🚀 Overview
Welcome to the Home Loan Dashboard, a powerful and interactive visualization tool built with Power BI. This dashboard provides deep insights into the home loan dataset, revealing key patterns and trends in loan distribution, recovery, and customer behavior across various branches in India.

## 📁 Dataset Description
The dataset includes the following columns:
- **Branch**: Location of branches where loans are processed.
- **Channel**: Application channels used by customers.
- **Customer**: Unique customer data.
- **Dates**: Key dates such as application, sanction, and recovery.
- **Product**: Types of home loan products.
- **Recovery Data**: Information on loan recoveries.
- **Sanction Data**: Details on sanctioned loans.

## 🛠️ Data Processing and Model Building
### Data Cleaning
- Removed duplicates and handled missing values.
- Standardized data formats for consistency.

### Data Transformation
- Employed DAX functions to create calculated columns and measures.
- Established relationships between tables with appropriate cardinality settings.

## 📊 Dashboard Features
### Visual Components
1. **Loan Distribution Funnel**: Explore the journey of loan applications from start to finish.
   
2. **Total Recovery Amount by Products (Pie Chart)**: Click on different slices to see detailed recovery data by product.

3. **Map Chart on Branch Locations in India**: Zoom in and out to see branch distribution and click on specific locations for branch-specific insights.

4. **Bar Chart on Total Applied Loans by Products**: Hover over the bars to see exact numbers, filter by product categories.

5. **Line Chart on Total Applied Loans by Years, Quarters, and Months**: Adjust the timeline to analyze trends for specific periods.

6. **Key Influencers Visual**: 
   - Understand what factors increase the likelihood of loans > 10 being approved.
   - Example Insight: "The probability of an applied loan amount > 10 being 'Yes' increased the most (2.20 times) when the applicant’s age was between 26-32 years."
   - Explore other influencing factors like channels, products, and customer demographics.

7. **Q&A Visual**: Ask natural language questions like:
   - "What is the total applied loan amount?"
   - "Show top 10 product names by total customer count."
   - Get instant visual responses to your queries.

8. **Decomposition Tree**: 
   - Break down applied loans > 10 by age, product, and channels.
   - Click through branches to explore detailed data layers.

## 🔑 Key Insights
- **Recovery Success**: Certain products lead in recovery amounts, highlighting effective collection strategies.
- **Seasonal Trends**: Peaks in loan applications suggest opportunities for targeted marketing.
- **Customer Segments**: Age group 26-32 shows higher loan application amounts, presenting a key target demographic.
- **Branch Performance**: Major city branches dominate in application volume, as seen on the map.

## 🎯 How to Use This Dashboard
1. **Interact with Visuals**: Click, hover, and filter across various charts for detailed data exploration.
2. **Ask Questions**: Use the Q&A feature to interact directly with the data.
3. **Deep Dive with Decomposition Tree**: Analyze loan applications by diving into specific attributes like age, product, or channel.
4. **Customize Views**: Use slicers and filters to tailor the dashboard to your specific needs.

## 🔍 Future Enhancements
- **Predictive Analytics**: Add models to forecast future loan trends.
- **Real-Time Data**: Integrate live data feeds for up-to-date insights.
- **Enhanced Demographics**: Expand the dashboard with additional customer demographics for richer analysis.

## 📬 Get in Touch
Have questions, feedback, or suggestions? Reach out to [Naman Shrimali] at [namanshrimali21@gmail.com].

---

✨ Dive into the dashboard and start uncovering insights that drive data-driven decisions in the home loan sector. Happy analyzing!
