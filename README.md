#  DA_BI_SuperFood
## *Business Analytics and Visualization for Super Foods Max*
This project was developed as part of a course at RMIT, where I applied data analysis and visualization techniques using Python. The goal was to support Super Foods Max in increasing sales revenue by 5% over the next two years by analyzing customer behaviour and identifying actionable insights.

     
### Project Outline:

### 1. Business Questions: 

How can we increase the average spend of our loyal customers and encourage them to make repeat purchases?     
How can we encourage first-time customers to become regular and loyal customers?     
What is the number of customers who are both loyalists and first-time buyers, grouped by their household diversity?     
Which items are being purchased by loyal customers and first-time customers?     
What is the department with the highest revenue?     
What is the sales trend for both loyal customers and first-time buyers over time?     

### 2. Acquire Data:

We utilized a dataset provided by RMIT that contains transaction details for Super Foods Max from 2020 to 2022. This includes customer information, product details, and transaction dates. The dataset was used to identify trends and patterns related to customer behaviour and sales performance.

### 3. Data Cleaning and Formatting:
 
Dropped records from 2022 due to incomplete data.     
Removed 118 duplicate records from the dataset.   
![image](https://github.com/user-attachments/assets/db8b477d-90fb-4cce-932e-119f673d1295)

Replaced values in the "loyalty" column (e.g., "Promiscuous" was changed to "Non-Loyalist").     
Converted the "transaction_date" column to a datetime format and created new "year" and "month" columns for analysis.     
Removed the "store" column, as it was not relevant to our analysis.

### 5. Data Analysis and Visualization:
 
Various visualizations were created to provide insights into customer behaviour and sales trends. These included:
Sales trends over time for both loyal customers and first-time buyers.
A breakdown of items purchased by each customer group.
Department-wise revenue analysis to identify the most profitable categories.

Here's a brief Python code snippet used to generate the sales trend visualizations:

*Figure 1: Loyalist Household Customer Numbers*
![fig1 Code](https://github.com/user-attachments/assets/1feec07b-ce28-44fe-8cbe-a84934363ed6)

This figure shows the number of loyal customers in each household type. By grouping data by household type and filtering for loyal customers, you can see which household groups are more likely to remain loyal to Super Foods Max.
Insight: Larger households may represent higher numbers of loyal customers, which can help guide future marketing efforts toward those households.

*Figure 2: First-Time Buyer Household Customer Numbers*
<img width="630" alt="image" src="https://github.com/user-attachments/assets/477283a7-783a-4803-bde5-e8785af2528f">

This bar chart shows the number of first-time buyers by household type. It's useful to identify household diversity in first-time buyers and help segment marketing strategies to convert these customers into loyal ones.
Insight: Understanding which household types bring the most first-time buyers can help focus efforts on converting these customers into regular buyers.

*Figure 3: Loyalist Department Trends Over Time*
<img width="648" alt="image" src="https://github.com/user-attachments/assets/4190eef8-bb52-4864-834d-d64b35992b0a">

This line plot illustrates the revenue trends for different departments based on loyalist customers across the years. Each line represents a department, showing how revenue from loyal customers has evolved over time.
Insight: Identifying departments that consistently generate high revenue from loyal customers can help in product promotion and stock management. Departments with declining trends may need special attention.

*Figure 4: First-Time Buyer Department Trends Over Time*
<img width="727" alt="image" src="https://github.com/user-attachments/assets/8c94a934-befa-4bb1-8a94-af1b501302f8">

Similar to Figure 3, this line plot tracks the revenue trends for first-time buyers by department over the years. It helps highlight which departments perform well with new customers.
Insight: Departments that consistently attract new buyers can be prioritized for promotions. Departments showing strong growth in first-time buyers may represent opportunities for customer retention strategies.

*Figure 5: Loyalist Commodity Revenue*
<img width="651" alt="image" src="https://github.com/user-attachments/assets/8b290f93-1ea9-403e-8fe8-0f2251076be7">

This bar chart visualizes the top 15 commodities generating the highest revenue from loyal customers. It helps identify which products are most popular among the loyalist customer group.
Insight: The identified top commodities can help Super Foods Max prioritize stock, marketing, and promotional efforts on these high-revenue items to further engage loyal customers.

*Figure 6: First-Time Buyer Commodity Revenue*
<img width="692" alt="image" src="https://github.com/user-attachments/assets/d0139563-840f-4718-8cd6-683f905c7bf5">

This bar chart displays the top 15 commodities generating the most revenue from first-time buyers. It highlights which products attract new customers.
Insight: Super Foods Max can use this information to design targeted promotions for first-time buyers, encouraging repeat purchases by highlighting these popular products.

*Figure 7: Loyalist Revenue Trends by Year/Month*
<img width="636" alt="image" src="https://github.com/user-attachments/assets/a8218da6-7c16-42f1-a767-c0098c775fb8">

This time-series line plot shows monthly revenue trends for loyal customers over multiple years. The visual helps identify seasonal or monthly peaks and dips in loyal customer spending.
Insight: Seasonal trends can inform decisions about product stocking, marketing campaigns, and loyalty programs to maintain or boost revenue during slow periods.

*Figure 8: First-Time Buyer Revenue Trends by Year/Month*
<img width="672" alt="image" src="https://github.com/user-attachments/assets/eef535bd-7879-42d9-8f48-b91da0758b38">

This time-series line plot shows the monthly revenue generated by first-time buyers. It provides insight into when new customers are most active and helps pinpoint periods of high or low sales from first-time buyers.
Insight: Understanding the revenue patterns for first-time buyers can help create strategic interventions at the right times to encourage repeat purchases and customer loyalty.


### 6. Conclusion:
The analysis offers valuable insights into Super Foods Max's customer behavior and revenue trends. By identifying the top commodities purchased by both loyal and first-time customers, the company can focus its marketing and stock efforts on high-performing products. The revenue trends by month and year for both customer segments highlight seasonal patterns, allowing for more targeted promotional campaigns and inventory management. For loyal customers, emphasizing their preferred products and engaging them during peak periods can help maintain or increase their spending. Meanwhile, identifying opportunities to convert first-time buyers into loyal customers by analyzing their purchasing habits and optimizing timing for promotions will be crucial in driving repeat purchases and fostering long-term loyalty. These insights provide actionable strategies to help Super Foods Max achieve its goal of increasing sales revenue by 5% over the next two years.
