# AUTOMOBILE SALES ANALYSIS

_COMPANY_: CODTECH IT SOLUTIONS

_NAME_: AARTHI N

_INTERN ID_: CT04DY248

_DOMAIN_: DATA ANALYTICS

_DURATION_: 4 WEEKS

_MENTOR_: NEELAM SANTOSH

**PROJECT DESCRIPTION**:

The **Auto Sales Analysis** project is a comprehensive data analytics and visualization aimed at understanding vehicle sales performance across different dimensions such as time, geography, vehicle type, dealer performance and customer preferences. By leveraging Microsoft Power Bi, this project transforms raw sales data into interactive and insightful dashboard that enables business stakeholders to make informed, data-driven decisions.

**TOOLS AND TECHNOLOGIES USED**:

  * **Power Bi Desktop**: The primary tool used to build the dashboard. It allowed importing, cleaning, modelling and visualizing data in an user-friendly and interactive manner.
  * **Power Query**: Used for **ETL (Extract, Transform, Load)** process. With Power Query raw datasets were cleaned, null values handled, column names standardized, and unnecessary fields removed.
  * **DAX (Data Analysis Expressions)**: Applied for creating calculated columns, measures, and key performance indicators (KPIs) such as Total Sales, Year-over-Year growth, Average sales per Dealer, and Profit Margin.

**METHODOLOGY AND WORKFLOW**:

The workflow of this project can be broken down into the following stages:

  1. **Data import and Preparation**:

     Raw auto sales data was imported into Power Bi. The dataset contained fields such as sales transaction Id, dealer name, vehicle model, category, sales amount, units sold, date of sale and location. Using **Power Query**, the dataset was cleaned: duplicate rows were removed, missing values addressed and derived columns were created for time-based analysis.

  2. **Data Modeling**:

      Relationships were established between fact and dimension tables. The star schema design allowed for smooth slicing and dicing of sales performance.

  3. **Creating calculations and KPIs with DAX**:

      Several measures were created to enrich analysis. Examples include:

       * Total Sales = SUM(Sales[Amount])
       * Total Units Sold = SUM(Sales[Quantity])
       * YoY Growth = (CurrentYearSales - PreviousYearSales) / PreviousYearSales
       * Profit Margin = (Sales - Cost) / Sales

      These KPIs provided actionable insights into performance trends.

  4. **Visualization and Dashboard Design**:

      An interactive dashboard was built with visuals such as:

       * **Line charts**: showing sales trends over months, years and quarters.
       * **Bar/Column charts**: comparing sales by vehicle type, dealer and region.
       * **Pie/Donut charts**: showing market share by category or brand.
       * **Maps**: displaying geographical distribution of auto sales across regions.
       * **KPIs cards**: summarizing key values such as total revenue, units sold and growth percentage. Fillers and slicers were added to allow users to drill down by vehicle type, dealer or region.

  5. **Insights & Business value**:

      The dashboard highlighted critical patterns such as:

        * Which vehicle categories contributed most to total sales.
        * Seasonal trends in auto sales.
        * Performance comparison among dealers and regions.
        * Identification of underperforming products or area requiring promotional strategies.

  6. **Deployment and sharing**:

      The final dashboard was published to the Power Bi service. With automatic refresh enabled, the dashboard provided real time updates whenever new sales data was added.

**CONCLUSION**:

  This project showcases how **Power Bi** can be leveraged to transform raw auto sales data into a decision making tool. By combining data modeling, DAX calculations, and rich visualizations, the dashboard not only tracks historical sales but also provides predictive insights into future performance. The insights gained can guide pricing strategies, marketing campaigns, inventory planning, and customer engagement initiatives. Ultimately, this project emphasizes the role of **business intelligence** in improving organizational efficiency and boosting profitability in the highly competitive automotive sector.
         
     
     
