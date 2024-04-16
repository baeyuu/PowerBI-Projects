# PowerBI-Projects
A repository of Power-Bi projects done while learning and on internship

### Project Overview

1. Sales Dashboard: This project provides insight into the sales performance of a Supermarket company for the calendar year 2019. By analyzing various parts of the sales and Financial data, we seek to identify trends, make Data-inspired Recommendations and understand the company's Financial performance.
2. Churn: This project provides insight into the operations of a Telecom company. The churn rate was the major metric, but exploration was done to understand the factors and characteristics of the churned customers for recommendation purposes.
3. Call Centre: This is data that explores the efficiency of call centre agents, by measuring the performance of each agent based on some key performance metrics.
4. Covid: This project is a United States covid 19 tracking dashboard, basically focusing on tracking the daily report, confirmed cases and deaths of covid 19 from January 2020 to August 2021.

### Data Sources 

1. Sales Dashboard: The Primary dataset used for this analysis is the "Expenses, Revenue, and Product Datasets" which contains detailed financial information about the company
2. Churn: the primary dataset was obtained from the PWC internship platform, which is about a Telecoms company user activity.
3. Call Centre: Also this data is obtained from the PWC Internship platform but focuses on the Telecom company's call centre agent performance.
4. Covid: The data is gotten from USAFacts. it is connected to an online database which gives a live update as the comes live.

### Methodology

1. Sales Dashboard: Fact tables(Expenses and Revenue), Dimension Table(Product and Account) further modelling was done to create a date, account header and simulations table.
   Dax measures were also created to calculate financial metrics such as Gross margin, %gross margin, and monthly income statements.
2. Churn Analysis: A data Exploration of the Demography, Product details and Account details of the customers were explored, also further breakdown of these customer details was delved into, especially for the churned customers. Finally, a risk analysis was done  using the churn condition, internet service duration contract type of the customer as a filter
3. Call centre: Dax measures were created to extract the performance of individual agents from the performance data of the company.
4. Covid: This interactive feature aggregates data from the Centers for Disease Control and Prevention (CDC), and state- and local-level public health agencies. County-level data is confirmed by referencing state and local agencies directly


### Result and Recommendation

1. Sales Dashboard:
   - it was observed that the highest revenue and Gross margin was gotten in November, but the highest percentage gross margin was in January.
   - The retail Team is the highest revenue generating team with a revenue of 3.9 million
   - Kappa Drinks is the most profitable supplier with a percentage gross margin of 56%
   - Recommendations are included in the financial simulator with what-if conditions considering varying costs, Quantity of produce, unit price and expenses.
2. Churn Analysis:
   - The largest percentage of the customer base are Single/Young people, which indicates that the company needs to work on improving their product to meet the young peopple needs.
   - Internet services products are the major reason for customer churning, the company needs to work on its Internet service and related products.
   - There is also a need to check into strategies to retain new customers, most of the churned customers are new customers who have spent less than a year.
3. Call Centre:
   - The average customer satisfaction  is very low compared to industry standard
   - The highest-performing agents are Stewart, Joe and Diane, while the lowest-performing are; Jim, Dan and Martha. There is a need to improve on payment resolution training for agents.
   - There are more resolved complaint(72%) than unresolved ones (27%)
4. Covid:
   -  A total confirmed COVID-19 case of 36.16 million cases were recorded, and a recorded death of 615.38 thousand leaving a fatality rate of 1.7%
   -  The state of California recorded the highest number of cases of 4.033 million people and a total death of over 64 thousand people. But the state of Massachusetts has the highest fatality rate.
   -  consult medical experts for recomendation.
