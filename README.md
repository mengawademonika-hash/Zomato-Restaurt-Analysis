Zomato Restaurant Data Analysis
📌 Project Overview
The Zomato Restaurant Data Analysis project demonstrates an
end-to-end data analytics workflow---from relational database management
and SQL querying to Power BI dashboards and actionable business
intelligence reporting.
The primary objective is to analyze Zomato's operational and
transactional data to uncover insights into customer ordering behavior,
cuisine preferences, restaurant performance, and revenue distribution.
👥 Project Team: Select Star ⭐
- Yukta Jaysingpure
- Monika Mengawade
- Akash Jadhao
- Revan Gunjal
🔄 Analytical Workflow
1. Dataset and Schema Design: Built and normalized a MySQL
   relational database modeling Zomato's ecosystem across multiple core
   tables.
2. SQL Analysis: Used aggregate functions (SUM, COUNT, AVG),
   joins, subqueries, and window functions to identify business
   patterns.
3. Dashboard and Visualization: Integrated Power BI dashboards to
   visualize KPIs, monthly trends, city-wise demand, and restaurant
   ratings.
4. Insights and Recommendations: Translated quantitative findings
   into business actions to address customer satisfaction risks and
   identify revenue opportunities.
📊 Database Schema and Table Inventory
  Table Name                 Row Count         Column Count Key /
                                                            Relationships
  users                      100,000                   10 user_id
                                                            (Primary Key)
  restaurant                 148,541                   12 id /
                                                            restaurant ID
                                                            (Primary Key;
                                                            verify exact
                                                            column name)
  orders                     150,281                    6 user_id and
                                                            r_id (Foreign
                                                            Keys)
  menu                     1,179,936                    5 menu_id
                                                            (Primary Key),
                                                            r_id and f_id
                                                            (Foreign Keys)
  food                       371,561                    3 f_id (Primary
                                                        Key)
Note: Confirm the row counts, column counts, and key definitions
against the final database before publishing.
💡 Key Business Findings and Insights
- Top-Selling Restaurants: A small group of high-performing
  restaurants may account for a substantial share of marketplace
  revenue.
- Cuisine Demand: Popular cuisine groupings, including North
  Indian and Chinese variants, appear among the leading categories in
  the analyzed results.
- Customer Retention: Analysis distinguishes repeat customers from
  one-time users, highlighting opportunities for targeted loyalty and
  retention campaigns.
- Rating Impact and Anomalies: Restaurant ratings can be compared
  with order volumes to identify high-revenue restaurants with low
  ratings that may need service-quality reviews.
Validate each finding against the actual query outputs before
presenting it as a confirmed result.
🚀 Recommendations
- Quality Assurance: Investigate low-rated restaurants that
  generate substantial revenue to help protect customer trust and
  improve service consistency.
- Targeted Marketing: Consider expanding promotions and partner
  availability for high-performing cuisines in high-demand cities.
- Customer Retention Programs: Develop engagement campaigns to
  encourage one-time customers to place repeat orders.
- Performance Monitoring: Track key metrics such as total orders,
  revenue, average order value, customer activity, and restaurant
  ratings in a Power BI dashboard.
🧰 Tools and Technologies
- Database: MySQL
- Query Language: SQL
- Visualization: Power BI
- Analysis Techniques: Data modeling, joins, aggregation,
  subqueries, window functions, KPI analysis
✅ Conclusion
This project demonstrates how SQL and Power BI can be used together to
organize restaurant and order data, analyze marketplace performance, and
communicate business insights. The findings can support better decisions
around restaurant quality, cuisine marketing, and customer retention.
👤 Contributors
Select Star Team: Yukta Jaysingpure, Monika Mengawade, Akash Jadhao,
and Revan Gunjal.
