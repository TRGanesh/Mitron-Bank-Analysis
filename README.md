# Mitron Bank Analysis
**A Project from CodeBasics Resume Challenge**

#### Tableau Dashboard Link : [My Dashboard](https://public.tableau.com/app/profile/tr.ganesh/viz/MitronBankData/MainDashboard1)
#### Video Presentation Link : [Youtube Video](https://youtu.be/_rjBEin3_1k?si=F0853Oo2sqj71EgJ)
---

### **About the Company**
Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market.

### Task : Providing Insights to the Product Strategy Team in the Banking Domain
### About Data:
To CSV files were provided,
1. dim_customers
2. fact_spends

**Column Description for dim_customers:**
<pre>
<b>customer_id</b> : This column represents the Unique ID assigned to each customer.
<b>gender</b> : This column represents the gender of the customer. (Male, Female)
<b>age_group</b> : This column categorizes the customer into different age groups. (21-24, 25-34, 35-45, 45+)
<b>marital_status</b> : This column indicates the marital status of the customer (single, married).
<b>city</b> : This column represents the city of residence for the customer. (Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru)
<b>occupation</b> : This column denotes the occupation or profession of the customer. (Salaried IT Employees, Salaried Other Employees, Business Owners, Freelancers, Government Employees)
<b>average_income</b> : This column indicates the monthly average income of the customer, in INR currency.
</pre>

**Column Description for fact_spends:**
<pre>
<b>customer_id</b> : This column represents the Unique ID of each customer, linking to the dim_customer table.
<b>month</b> : This column indicates the month in which the spending was recorded. (May, June, July, August, September, October)
<b>category</b> : This column describes the category of spending (Entertainment, Apparel, Electronics, etc).
<b>payment_type</b> : This column specifies the type of payment used by the customer (Debit Card, Credit Card, UPI, Net Banking).
<b>spends</b> : This column shows the total amount spent by the customer in the specified month, category and payment_type.
</pre>
---
#### **Objectives :** 
- Uni-Variate & Multi-Variate Analysis 
- To understand Spending Behaviour among different Types of Customers 
- To Identify Relation between Customers Income & Spending 
- To Identify Customers who are using Credit Card mostly 
- Observing Spend-Income Ratio among different Occupations
---
#### Tools Used : Tableau, Python
#### Insights :
- People of 35-45 & 25-34 age group, having more Income and more Spending 
- Salaried IT Employees are Spending more, followed by Business Owners and Freelancers
- Top 4 Categories on which more spending(on average) is being done are Bills, Groceries, Electronics, Health & Wellness
- As per the Scatterplot between Income & Spend, Occupation would be a better feature to Cluster the Customers
- Top 2 widely used Payment types are Credit Card and UPI

#### Recommendations :
- Provide Offers to the People of the age range 25-34 & 35-45, Salaried IT Employees
- Provide Offers on Bills, Groceries, Electronics, Health & Wellness, Travel Categories
- Considering the Spend-Income Ratio, it's evident that IT professionals and freelancers allocate a significant portion of their earnings. Recognizing this trend, they emerge as a strategic first choice for customer targeting.
---
### About Tableau
Tableau is a Powerful Data Visualization Software that allows users to create Interactive and Shareable Dashboards and Reports. It enables users to connect to Various Data Sources, such as Databases, Spreadsheets, or Cloud Services, and then create visualizations like Charts(Bar Charts, Pie Charts), Graphs(Line Plots, Scatter Plots), Maps, and Dashboards to explore and understand the data.

**Features :**
- Data Connectivity : includes connectivity with Databases(SQL, NoSQL), Spreadsheets(Excel, CSV), Cloud Services(Google Analytics, Salesforce), and Big Data Platforms(Hadoop, Amazon Redshift)
- Drag & Drop Interface : various options includes Text Tables, HeatMaps, Geographical Maps, 
- Visualization Options
- Dashboard Creation
- Intuitive Filters, Parameters, Actions
- Data Blending and Joining
- Calculations and Expressions
- Advanced Analytics
- Collaboration and Sharing

---
### Different Plots used
#### **Pie Chart**
- 
