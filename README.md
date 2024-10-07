# CMPG 323 Project 5 - 39990966

## 1. Project Overview
The **NWU Tech Trends Benefit Realisation Report** is designed to provide an interactive view of the time savings realized by various clients and projects. Developed using **Power BI**, this report enables stakeholders to monitor and evaluate key metrics, project statuses, and client performance, emphasizing time savings and efficiency.

## 2. Report Pages and Features

### 2.1. High-Level Metrics Page
- **Purpose**: Summarizes crucial data points for decision-making.
- **Features**:
  - Summary view displaying counts of key metrics such as total time savings, number of projects, and clients.
  - Visualizations providing an overview of time savings across all clients and projects.

### 2.2. Client Monitoring Page
- **Purpose**: Allows monitoring of time savings at a client-specific level.
- **Features**:
  - Visual displays of time savings per client.
  - Time-based breakdown of savings changes over time for each client.

### 2.3. Project Monitoring Page
- **Purpose**: Offers a detailed view of ongoing projects and their performance.
- **Features**:
  - Visuals showing the total number of projects.
  - Three key metrics providing insights into project offerings.
  - Visualizations of savings accumulation over time and client associations for each project.

## 3. Filters
To enhance data analysis flexibility, the following filters are available across pages:
- **Project Filter**: Filter the report based on specific projects.
- **Client Filter**: Filter data for a specific client.
- **Date Range Filter**: Filter data by a custom date range.

These filters facilitate quick drilling down into data for tailored insights.

## 4. AI Features
The report incorporates **four AI features** to enhance analytics:
- **Anomaly Detection**: Identifies unusual trends in project savings and client performance.
- **Forecasting**: Predicts future savings based on historical data.
- **Decomposition Tree**: Analyzes data hierarchically, allowing for drill-down insights.
- **Q&A Feature** (Bonus): Users can ask natural language questions to gain insights from the dataset.

## 5. Live Connection and Scheduled Refresh

- **Live Connection**:
  - **Definition**: Queries data directly from the source without storing it in Power BI’s memory.
  - **Applicable Data Sources**: 
    - Azure Analysis Services
    - SQL Server Analysis Services Tabular
    - SQL Server Analysis Services Multi-Dimensional
    - Power BI Service Dataset

- **Excel File Connection**:
  - **Limitation**: Excel files cannot utilize a live connection.
  - **Solution**: Implement a **scheduled refresh** to update data at regular intervals.

Live connections are ideal for scenarios requiring real-time data access.

## 6. How to Use the Report

### A. Accessing the Report
1. Open the report in Power BI by navigating to the assigned workspace.
2. Use the navigation panel to switch between the `High-Level Metrics`, `Client Monitoring`, and `Project Monitoring pages`.

### B. Interacting with the Report
- **Filters**: Utilize filters on the right-hand side to focus on specific clients, projects, or time periods.
- **Visual Interactions**: Click on visualizations to drill down into more granular data.
- **Export Data**: Use the **Export Data** option within each visual to download underlying data.

### C. Data Security
Data connections are securely configured to ensure the protection of sensitive information. Only authorized users with appropriate access levels can view or interact with the data.

## 7. AI Features Usage

### A. Anomaly Detection
- **How to Use**: Navigate to the designated AI features page and review the identified anomalies in project savings. Use this information to investigate underlying causes.

### B. Forecasting
- **How to Use**: Access the forecasting section to view predicted savings. Adjust the parameters if necessary for more tailored predictions.

### C. Decomposition Tree
- **How to Use**: Click on the tree visual to drill down into project and client data. This feature allows you to explore the data hierarchy and identify specific areas of interest.

### D. Q&A Feature
- **How to Use**: Utilize the Q&A box to type in natural language questions. For example, "What were the total savings for Client A in Q1?" The system will generate a visual response based on the data.

## 8. References
The following resources were used during the development of this report:

1. Microsoft, n.d. *Power BI Documentation*. [online] Available at: <https://learn.microsoft.com/en-us/power-bi/> [Accessed 21 September 2024].

2. Fabric Community, 2024. *Data Cleaning Techniques in Power BI*. [online] Available at: <https://community.fabric.microsoft.com/t5/Desktop/Cleaning-Data-In-PowerBi/td-p/3061070> [Accessed 23 September 2024].

3. Russo, M. (2022) *Calculated Columns and Measures in DAX*. SQLBI. [Online] Available at: <https://www.sqlbi.com/articles/calculated-columns-and-measures-in-dax/> [Accessed 23 September 2024].

4. Oyinbooke, O. (2023) *Power BI AI Features for all Data Analysts*. Microsoft Tech Community. [Online] Available at: <https://techcommunity.microsoft.com/t5/educator-developer-blog/power-bi-ai-features-for-all-data-analysts/ba-p/3835447> [Accessed 24 September 2024].

5. Microsoft, n.d. *Building a Power BI Report*. [online] Available at: <https://learn.microsoft.com/en-us/power-bi/report-server/quickstart-create-powerbi-report> [Accessed 25 September 2024].

6. Fabric Community, 2024. *Best Practices for Designing Power BI Reports*. [online] Available at: <https://community.fabric.microsoft.com/t5/Developer/Power-BI-Design-Best-Practices/m-p/3541539> [Accessed 25 September 2024].

7. Microsoft, n.d. *Power BI Performance Optimization Techniques*. [online] Available at: <https://learn.microsoft.com/en-us/power-bi/guidance/power-bi-optimization> [Accessed 25 September 2024].

8. Edureka, n.d. *Power Query in Power BI*. [online] Available at: <https://www.edureka.co/blog/introduction-to-power-query/> [Accessed 25 September 2024].

9. Microsoft, n.d. *Visualizations in Power BI*. [online] Available at: <https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-types-for-reports-and-q-and-a> [Accessed 25 September 2024].

10. Inforiver, n.d. *Data Storytelling and Advanced Visualizations in Power BI*. [online] Available at: <https://inforiver.com/storytelling-advanced-visualizations-powerbi/> [Accessed 25 September 2024>.

11. Microsoft, 2023. *Types of filters in Power BI reports*. [online] Available at: <https://learn.microsoft.com/en-us/power-bi/create-reports/power-bi-report-filter-types> [Accessed 26 September 2024].

12. Microsoft, n.d. *Combo Chart in Power BI*. [Online] Available at: <https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-combo-chart?tabs=powerbi-desktop> [Accessed 27 September 2024].

13. Microsoft, n.d. *Implementing Row-Level Security (RLS) in Power BI*. [online] Available at: <https://learn.microsoft.com/en-us/power-bi/admin/service-admin-rls> [Accessed 28 September 2024].

14. Microsoft, n.d. *Best practices for Power BI data modeling*. [online] Available at: <https://learn.microsoft.com/en-us/power-bi/guidance/star-schema> [Accessed 28 September 2024].

15. Russo, M. (2023) *Optimizing DAX expressions involving multiple measures*. SQLBI. [Online] Available at: <https://www.sqlbi.com/articles/optimizing-dax-expressions/> [Accessed 28 September 2024].

16. Russo, M. and Ferrari, P. (2019) *DAX Patterns*. SQLBI. [Online] Available at: <https://www.daxpatterns.com/> [Accessed 28 September 2024>.

17. Rad, R. (2022) *Live Connection; When Power BI Comes Hybrid*. [Online] Available at: <https://radacad.com/live-connection-when-power-bi-comes-hybrid> [Accessed 29 September 2024].
    
18. Microsoft Learn, 2024. Power BI Guidance Documentation. [online] Available at: https://learn.microsoft.com/en-us/power-bi/guidance/ [Accessed 3 October 2024].

19. ScaleupAlly, 2024. Best Power BI Report Examples. [online] Available at: https://scaleupally.com/power-bi-report-examples/ [Accessed 5 October 2024].

20. VBeyond Digital, 2024. Power BI Trends and Predictions. [online] Available at: https://vbeyonddigital.com/power-bi-trends-2024/ [Accessed 5 October 2024].
    
21. Microsoft Power BI Blog, 2024. Power BI September 2024 Feature Summary. [online] Available at: https://powerbi.microsoft.com/en-us/blog/september-2024-feature-summary/ [Accessed 5 October 2024].

22. Numerro, 2024. The Complete Guide to Designing Power BI Reports. [online] Available at: https://www.numerro.io/power-bi-report-design-guide/ [Accessed 6 October 2024].

23. Microsoft Learn, 2024. Power BI Implementation Planning. [online] Available at: https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-introduction [Accessed 6 October 2024].
    
24. Inforiver, 2024. Storytelling and Advanced Visualizations in Power BI. [online] Available at: https://inforiver.com/storytelling-advanced-visualizations-powerbi/ [Accessed 6 October 2024].
    
25. SQLBI, 2024. Optimizing Power BI Reports: Best Practices for Performance and Usability. [online] Available at: https://www.sqlbi.com/articles/optimizing-power-bi-reports/ [Accessed 25 September 2024].


For any questions or feedback regarding the report, please reach out to **Jackson** at **39990966@mynwu.ac.za**.
