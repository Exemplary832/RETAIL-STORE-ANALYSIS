# RETAIL-STORE-ANALYSIS
### PROJECT OVERVIEW
In this project, data of a fictional retail store was obtained from Kaggle Datasets, which contained over 1000 rows of synthetic data representing the store’s sales transactions for the year 2023 and 2 days for January, 2024. The aim of the analysis was to glean insights of the business performance for 2023, which can be used to improve business operations in areas lagging and predict customer’s behavior. 
### DATA SOURCE
Kaggle dataset
### TOOL USED
Excel
### BUSINESS QUESTIONS
- Total sales, transactions, and quantity
- Sales by age category
- Sales by gender
- Monthly sales trend
- Product by age category
### SKILLS DEMONSTRATED
 Data cleaning, transformation, visualization
### ANALYSIS PROCESS
- Data exploration
- Data validation, 
- Data cleaning, 
- Data analysis
- Visualization
### DATA EXPLORATION
For comprehension of the data, it was observed end to end. The data has over 1000 rows, and 9 columns bearing Transaction ID, Date, Customer ID, Gender, Age, Product Category. Quantity, Price Per Unit, and Total Amount. 



![Pre-cleaning](https://github.com/user-attachments/assets/9d9451e7-4734-4745-8bd3-28481828d79b)



### DATA CLEANING AND VALIDATION
The cleaning and transformation processes are essential to address errors and blanks, as well as inconsistent formatting and other data quality issues so as to remove unwarranted biases that might skew the analysis, and hence promote the reliability of the data, and inform business decisions for stakeholders of the retail business. 
 As mistakes could happen during the transformation process, copy of the data was made to have a reference of the raw data as a backup.
 Blanks were searched for using the conditional formatting in Excel. It was also utilized to aid easy visualization of duplicates and manipulation per column. 
 To achieve objective of the analysis, data from 2024 were deleted. 
 Extra columns- month, year were created using TEXT function from the date column. 
 IFS function was used to distribute age categories into young adult, middle-aged and old 




![Post-cleaning](https://github.com/user-attachments/assets/9b3e9ac8-0a6e-4cb1-9176-cc6e7c985761)


 
 ### DATA ANALYSIS AND VISUALIZATION
1. #### Total sales, transactions, and quantity
    Total sales, total number of transactions and quantity of products bought were calculated using PIVOT Sum. 
 


![PIVOT Tables](https://github.com/user-attachments/assets/ddd64e48-d475-4da0-b31f-db886d7d4906)

2. #### Sales by age category
   This was explained by the pie chart, which showed that young adults (18-39) were the highest buyers and the old (>=60) being the loweest with 10% rate



   ![Pie chart ](https://github.com/user-attachments/assets/45305568-a87e-422b-ba1a-c92779605297)

   
3. #### Sales by gender
   The bar chart clearly depicted the store's purchasing reality by sex, with females taking the highest number of customers




   
![Sales by Gender](https://github.com/user-attachments/assets/2142aa82-4099-4063-9943-a4673d7477ee)

   
4. #### Monthly sales trend
   The line chart was instrumental in answering this business question. The highest period of sales attained in 2024 was in May ($53150) , while the lowest was September ($23620). Other months with noticeable sales were October, Decmber and February. 










![Line Chart](https://github.com/user-attachments/assets/fc3b9514-99a8-4860-9937-c246c9c3ee9d)



   
   

  
5. #### Product by age category
   Young adults purchased beauty products than the other age groups, and middle-aged customers mostly bought electronics. The old were the least of customers in all of the product categories, which supported the earlier question of the age group with the lowest purchases. 
   


   
   ![Sales by product category](https://github.com/user-attachments/assets/e3fbb19b-1c97-4717-8907-8b1f37a179d8)




6. #### DASHBOARD
A dashboard bringing toegther the key insights and findingd guided by the above business questions.



![DASHBOARD 1](https://github.com/user-attachments/assets/84b0ab57-e9de-4c59-9ff4-9f06cc373a97)



### RECOMMENDATIONS
