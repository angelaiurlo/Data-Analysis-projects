# Data Analysis projects
Content:
- Dream Craft Sales and Orders
- Multinational Quarterly Sales Report
- Emerging Tech Skills Analysis
  
## Dream Craft Sales and Orders

### 📌 Project Overview
Dream Craft is a company specialized in producing and selling miniaturized classic car models and collectibles. Operating globally with multiple offices, the company aims to enhance sales performance and streamline data management using Snowflake for database centralization and Power BI for business intelligence.

This project involves building a comprehensive sales and order analytics dashboard in Power BI, utilizing data from Snowflake to provide real-time insights into revenue, customer trends, product performance, and sales representative effectiveness.
### 🎯 Objectives
- Centralize Sales Data: improve data accuracy and accessibility with Snowflake.
- Enhance Business Intelligence: implement Power BI dashboards for better decision-making.
- Monitor Sales Performance: track revenue, orders, and customer purchases.
- Improve Operational Efficiency: identify bottlenecks and streamline processes.

### 🗂️ Database Schema

The following tables were used to structure the data:
- Offices: Stores office locations and details.
- Employees: Contains employee and sales representative information.
- Customers: Includes customer details and assigned sales reps.
- Products and Product Lines: Stores product details, categories, and pricing.
- Orders and Order Details: Tracks customer orders and purchased products.
- Payments: Contains customer payment records.

### 🛠 Tools Used
- Database: Snowflake
- Visualization: Power BI
- Data Processing: SQL

## Multinational Quarterly Sales Report

### 📌 Project Overview
In this project I analyze data of a multinational bicycle manufacturer, operates sales globally. The executive board and sales management team require quarterly sales data to assess past performance and guide strategic decisions for the upcoming quarter.

This report provides an interactive data story, helping stakeholders gain insights into sales trends, regional performance, category analysis, and salesperson contributions.

### 🎯 Objectives
- Review and transform the dataset and identify the measures and fields needed to support the story. 
- Create a report in Power BI desktop by appropriate selection of chart.
- Drive insights from the story.

### 🛠 Tools Used
- Power BI desktop and Power BI Service
- DAX for advanced calculations

### 📁 Report Content
Executive Board Dashboard:
- Quarterly Sales Performance Overview
- Key Sales Trends (Regions, Categories, Salespersons)
- Summary of High/Low Performing Areas
- Strategic Insights for Decision Making

Sales Management Interactive Report:
- Granular breakdown of sales performance
- Filters and drill-down capabilities
- Detailed comparison with previous periods

## Emerging Tech Skills Analysis 

### 📌 Project Overview
This project aims to analyze emerging and in-demand technology skills using the latest Stack Overflow Developer Survey. The analysis helps a global IT consulting firm stay competitive by identifying trends in programming languages, database technologies, and development tools.

### 🎯 Objectives
- Identify the most in-demand programming languages, databases, and IDEs.
- Perform data wrangling and statistical analysis to uncover key insights.
- Develop interactive visualizations using IBM Cognos Analytics.
- Present findings in a structured and meaningful way.

### 🛠 Tech Stack and Tools Used
- Python (for data extraction, cleaning, and analysis)
- Pandas, NumPy, Matplotlib, Seaborn (data wrangling & visualization)
- IBM Cognos Analytics (dashboard visualization)
- PowerPoint (final presentation of insights)

### 📊 Methodology

Data Collection:
- Extracted data from developer surveys.

Data Wrangling & Cleaning:
- Cleaned, transformed, and structured data using Pandas.

Exploratory Data Analysis (EDA):
- Identified patterns in programming language demand, database adoption, and IDE usage.
- Used statistical techniques to detect trends.

Dashboard Creation & Visualization:
- Built an interactive IBM Cognos Analytics dashboard to present insights.

Presentation & Insights:
- Compiled findings into a PowerPoint presentation to communicate key takeaways effectively.

### 📁 Project Structure

```
📂 emerging-tech-skills-analysis  
│──  Survey_analysis_data   # Processed datasets  
│──  Survey_analysis_code   # Jupyter notebooks for data extraction, cleaning and analysis   
│──  Survey_dashboard       # Dashboard snapshots & charts  
│──  Survey_presentation    # PowerPoint presentation of findings  
```
