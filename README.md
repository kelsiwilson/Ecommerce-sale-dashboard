# E-commerce sales dashboard
A task to analyze a dataset, clean and show findings by creating an e-commerce dashboard in Excel
## Project Overview
This Project aims to provide actionable insights 
That will help improve product sales, customer satisfaction rates,
and how social media influences the  increase in product sales and ratings.
By analyzing the various aspects of the sales data,
We seek to uncover trends, analyze historical data and 
make data-driven recommendations for strategic improvements.
## Tools 
Excel and Python: To clean the data using Excel and Python, create a pivot table and dashboard
## Objective
This repository serves as a documentation resource to analyze product sales,
Customer satisfaction & Loyalty, Customer Product purchase by shipping preference,
Social media influence affects product purchases and rating
##Type of Analysis used
Exploratory Data Analysis: It involved exploring data to discover trends and questions
such as group category that spends more, customer satisfaction affects brand loyalty,
high-income customers are interested in discounts.
## Data cleaning & preparation
Step 1: Download the file from the link and Load and clean the data location in Python.
The Location column was cleaned in Python to ensure consistency and accuracy, first identified and handled special characters (e.g., Évry, Göteborg, Créteil, São Cristóvão) by normalizing text using Unicode standardization. Inconsistent spellings and formats, such as variations of "Paris 17," were standardized by mapping them to a unified name. Extra whitespaces were removed using .str.strip(), and text was converted to title case for uniform formatting. Since there were no missing values, no imputation was needed. Finally, a verification check was performed to confirm the uniformity of location names across the dataset.
Step 2: Open data in Excel and check each column and row for any errors or inconsistencies. 
Step 3: I notice on the Purchased Category, "Travel & Leisure Flights" was written as Travel & Leisure (Flights and "Packages" was written as Packages).
Step 4: WE cleaned using the find and replace method and erased the bracket.
Step 5: Create a pivot Table for Customer Satisfaction & Loyalty, Customer Product purchase by shipping preference,
Social media influence affects product purchases and rating
Step 6: Create a Dashboard in Excel using a bar chart, line chart, pie chart, Column chart etc..
## Screenshot of KPIs
![Screenshot 2025-03-24 165923](https://github.com/user-attachments/assets/83b26287-8d11-482f-9af0-b9069b9641d6)
Step 7: We use a card to visually display the KPIs.
Step 8: Two bar chat and a doughnut chart we included in the report design
1. The first chart represents the Age group that spends more between old and young.
   Young spend more than old
2. Customer satisfaction by brand loyalty 
3. High-income customers have an interest in discounts
 ## Snapshot of Dashboard
![Screenshot 2025-03-24 172314](https://github.com/user-attachments/assets/0373de65-491b-4e86-8047-623e52425336)
## Insights
1. The age group that spent more on products is the young group with $136,058.40
2. Customers don't often return purchased items and Customer Satisfaction
   is highly affected by brand loyalty.
3. Customers are very sensitive to discounts and Customers  with high income are interested in discount
4. Customers who purchase a particular product don't particularly use a particular shipping mode
5. Social media Influence highly affects product purchase and product rating
6. The product category with the highest return rate in Jewelry & accessories
## Recommendation Report
1. Tailor marketing  strategies toward young customers with trendy products like S/w & Apps, outdoors & gardening,
while older customers with toys & games and electronics.
2. Improve customer satisfaction through better product description and post-purchase support to reduce returns
3. Do discounts campaign and focus more on middle-income shoppers and introduce exclusive offers to high-income shoppers
4. Offer free shipping for high-valued and large quantities of products purchased
5. Invest more in social media campaigns for visually appealing products to target more customers for better engagement
6. Include detailed clear quality descriptions for all products to minimize return rate.

