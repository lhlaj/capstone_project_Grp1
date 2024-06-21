# Analysis and Visualization of Sourcing Request and Quotation Data for Sourcy

## Project Overview
This project aims to revolutionize global B2B sourcing and international trade by providing Sourcy with data-driven insights to enhance their procurement strategies. The project focuses on the analysis and visualization of sourcing requests and quotations from Sourcy's PostgreSQL database to identify trends and performance metrics among customers, products, and suppliers.

## Objectives
1. **Identify Trends and Performance**
   - Analyze GMV performance, including potential and gained GMV, total cost, and gross profit.
   - Evaluate the performance of product categories and SKUs, including quoted and purchased categories.
   - Assess sourcing requests (SR), including quantities, GMV per SR, and average initial quotations.

2. **Generate Actionable Insights**
   - Identify cross-sell and upsell opportunities.
   - Create data analytics reports for suppliers' insights.
   - Develop dashboards to provide quantities of DA requests, DA reports per DA, and category types per report.

## Dataset Description
- **Database**: 45 tables storing diverse information crucial to operations.
- **Platform**: DBeaver for database management.
- **Data Span**: From May 2024 onwards.
- **Key Data Points**:
  - Customer basic information
  - Geographic data (countries, regions, cities)
  - Sourcing requests and quotations
  - Product specifications
  - Shipping details
  - Supplier information
  - Customer-requested data analysis reports

To ensure data integrity, SQL scripts are used within the 'test_dwh' schema.

## Methodology & Findings

### GMV Performance
- **Methodology**: Extract approved data, calculate product and logistics revenue, convert amounts to CNY, create a new dataset for clean data storage.
- **Findings**: Total revenue is 195 million CNY, with product revenue at 54.3 million CNY and logistics revenue at 14 million CNY.

### Product Categories & SKUs
- **Methodology**: Create a new table by joining six tables to analyze product categories and SKUs.
- **Findings**: 'Home & Garden' is the top category for both quoted and purchased items.

### Sourcing Requests
- **Methodology**: Create a new dataset by joining relevant tables.
- **Findings**: The highest number of SKUs is in May 2024, with 'Home & Garden' being the most requested category.

### Data Analytics
- **Methodology**: Analyze the number of DA requests and reports.
- **Findings**: Customer 130 made the most DA requests, focusing on beauty and technology product categories.

## Challenges and Limitations
- **Time Scarcity**: Limited time for thorough database study.
- **Platform Adoption**: Initial phases of using DBeaver and Superset.
- **Dashboard Capabilities**: Limited robustness and comprehensiveness.
- **Large-scale Data Import**: Time-consuming and impacts efficiency.
- **Missing Values**: Some data values were missing during transfer.

## Future Work
- **Deeper Analysis of GMV Preference**: Explore factors driving GMV, conduct statistical analysis, and use advanced techniques.
- **ETL Automation**: Develop reusable ETL scripts, ensure data quality, and use data orchestration tools for efficiency.

## Conclusion
- **Business Model Understanding**: Crucial for project success.
- **Stakeholder Engagement**: Essential to meet expectations.
- **Tool Utilization**: Use Superset and PostgreSQL for data processing and visualization.
- **Project Timetable**: Establish clear milestones and timelines.
- **Effective Communication**: Maintain regular communication with stakeholders.
- **Continuous Review**: Regularly update the dashboard based on feedback.

## References
- Superset
- DBeaver

## Distribution of Work
- Dataset movement, cleaning, query scripts - All team members
- PowerPoint - All team members
- Final report - All team members
