# Business-Insights-360
A PowerBI dashboard build on Atliq Hardware which gives insights of Finance,sales, Marketing, Supply chain and Executive views.

Interactive DashBoard : [click here](https://app.powerbi.com/view?r=eyJrIjoiY2Y1ZTUzYjAtMjA3OS00OGFkLWI2OTEtNzdkYjlmMjFlMzZmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

LinkedIn Video Presentation : [click here](https://www.linkedin.com/posts/pampana-gopikrishna12_%3F%3F%3F%3F%3F%3F%3F%3F%3F-%3F%3F-%3F-%3F%3F%3F%3F-%3F-activity-7188809951077715968-agLT?utm_source=share&utm_medium=member_desktop)

Data Source Link : [click here](https://lnkd.in/gRwFAKKW)
# **About Company**
AtliQ Hardware Company which manufacturers Computer Hardware and Peripheral and supplies to many of their clients across india.It has head office in delhi and so many regional offices throughout India.

Atliq Hardware operates its business three regions in india 
1. Central
2. South
3. North

# **Problem Statment**
Atliq Hardware market growing Dynamically. But the sales director observed overall the sales are declining.He facea issue with in terms of tracking of the Sales.Company wants an PowerBI dashboard which gives quick and latest sales insights in order to take Data driven decision making.

# **AIMS grid**

![image](https://github.com/Yogananda-GopiKrishna/Atliq-Hardware-Sales-insights/assets/125633628/bdebb02c-d084-48b0-9a33-213d02c183ac)



# **Data source**
![image](https://github.com/Yogananda-GopiKrishna/Atliq-Hardware-Sales-insights/assets/125633628/2e95b6bc-cc8a-4cab-a442-2fee204ee6d4)

A. Sales database is downloaded from above link.
B. Imported and Loaded database using SQL.
C. Five tables are Exists in sales database.
D. All These Tables loaded in PowerBI Using MySQL.

        1. Customer Table
        2. Market Table
        3. Sales Transactions Table
        4. Product Table
        5. Date Table

# **Key Variables**
**Markets Table - Zone**

- Central -  Bhopal, Nagpur, Mumbai
- North – Surat, Patna, Lucknow, - Kanpur, Delhi NCR, Ahmedabad
- South –
Bhubaneswar, Hyderabad, Kochi, Bengaluru, Chennai

**Customers Table - Type of Customers**

- Brick & motor :  refers to a business that has at least one physical location that customers can visit. 
Ex : Croma, Vijay sales  …etc.
- E-commerce : refers to the process of buying and selling goods and services over the internet.
Ex : Amazon, Flipkart …etc.

**Products Table - Type of Products**
- Own Brand:  Products are Manufactured and Branded by Atliq hardware itself.
- Distribution: These Products are manufactured by External (3rd party) sources and resold by Atliq hardware by its own brand.

# **Data Description**

**Fact Tables :**  Observational events /Transactional Events contain dimension key columns that relate to dimension table.Relatively Large number of rows.
- Sales Transaction Table

**Dimension Table :** One of the columns containing at least one Unique Identifier , These are Descriptive columns and Relatively small number of rows.

- Customers table
- Markets Table
- Products Table
- Date Table

# **Data Modelling**

![image](https://github.com/Yogananda-GopiKrishna/Atliq-Hardware-Sales-insights/assets/125633628/4adc45fa-b69b-4f95-a842-6256fd265a9c)


# **Key Metrics**
- Revenue -- Total Sales amount
- Sales Quantity -- Total number of sales
- Total Profit Margin -- Total Profit Earned
- Profit Margin % -- Proportion of Profit earned relative to Revenue Generated
- Profit Margin Contribution % -- Proportion of Profit earned to Total Profit
- Revenue Contribution % -- Proportion of Revenue generated to Total Revenue
- Revenue LY (Last Year) -- Revenue of Last Year

# *Power BI Dashboard Overview*
**Home**
![image](https://github.com/Yogananda-GopiKrishna/Atliq-Hardware-Sales-insights/assets/125633628/9745b64b-fed7-445c-b4a4-c8a8a72e0013)

**Key Insights**
![image](https://github.com/Yogananda-GopiKrishna/Atliq-Hardware-Sales-insights/assets/125633628/ff8f4029-d0de-4660-97a7-e0a81e2581fe)

**Profit Analysis**
![image](https://github.com/Yogananda-GopiKrishna/Atliq-Hardware-Sales-insights/assets/125633628/a1380604-c2c8-4123-a16e-fafd7412d092)

**Performance Insights**
![image](https://github.com/Yogananda-GopiKrishna/Atliq-Hardware-Sales-insights/assets/125633628/bb1e06a8-fbd8-49ea-9334-a64d645f3f0e)


# **Major Insights**
- Over all years Delhi , Mumbai and Ahmedabad is Contributing 81% Revenue followed other Markets.
- Over all years Revenue falls down from 26.1M to 14.7M
- Over all years Electricaslara store contributing more Revenue almost 69%.
- Overall years North region is Higher in Revenue and Sales Quantity followed by Central and South.
- Brick and motor has 3 times more  Revenue and Sales Quantity than E-commerce.
- Although Delhi more Revenue Contribution % but Profit margin % is 2.3%.
- Overall Years Surat Market giving more PM% followed by Patna , Bhubaneswar and Bhopal.
- Revenue Contribution of Bhubaneswar is less But Profit Margin % increasing Year on Year.
- Chennai also Increasing PM% Year on year.
- Bengaluru has Lower Profit Margin % (~ -21%)
- Flawless store Customer in Bengaluru giving losses almost (~ 30%)  and Then Bengaluru Market No Transactions are there.




