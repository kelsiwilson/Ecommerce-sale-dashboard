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
Excel and Python: To clean the data using Excel and Python, create a pivot table and a dashboard
## Objective
This repository serves as a documentation resource to analyze product sales,
Customer satisfaction & Loyalty, Customer Product purchase by shipping preference,
Social media influence affects product purchases and ratings
##Type of Analysis used
Exploratory Data Analysis: It involved exploring data to discover trends and questions
such as group category spends more, customer satisfaction affects brand loyalty,
high-income customers are interested in discounts.
## Data cleaning & preparation
Step 1: Download the file from the link and Load and clean the data location in Python.
The Location column was cleaned in Python to ensure consistency and accuracy,
first identifying and handling special characters (e.g., Évry, Göteborg, Créteil, São Cristóvão)
by normalizing text using the Unicode standard. Inconsistent spellings and formats, 
such as variations of "Paris 17," were standardized by mapping them to a unified name.
Extra whitespaces were removed using .str.strip(), and text was converted to title case for uniform formatting.
Since there were no missing values, no imputation was needed.
Finally, a verification check was performed to confirm the uniformity of location names across the dataset.
Step 2: Open the data in Excel and check each column and row for any errors or inconsistencies. 
Step 3: I notice on the Purchased Category,
"Travel & Leisure Flights" was written as Travel & Leisure (Flights and, "Packages" was written as Packages).
Step 4: WE cleaned using the find and replace method and erased the bracket.
Step 5: Create a pivot Table for Customer Satisfaction & Loyalty, Customer Product purchase by shipping preference,
Social media influence affects product purchases and ratings
Step 6: Create a Dashboard in Excel using a bar chart, line chart, pie chart, Column chart etc..
## Screenshot of KPIs
![Screenshot 2025-04-21 145214](https://github.com/user-attachments/assets/ab67566e-4c1a-483d-879f-5b3e8ff4d580)
![Screenshot 2025-04-21 145351](https://github.com/user-attachments/assets/f7c181f7-5c16-433a-91d0-7f096ae95125)
![Screenshot 2025-04-21 145409](https://github.com/user-attachments/assets/47d4f666-b200-47f3-a14f-bc33bbe1a1e9)


Step 7: We use a card to visually display the KPIs.

 ## Snapshot of Dashboard
![Screenshot 2025-04-21 145030](https://github.com/user-attachments/assets/be8b17fb-aa58-4ae5-8d04-d4ce89c5e7a9)


## Insights
1. The age group that spent more on products is the young group, with a difference of $2,780.
2.  The high-income group earners spend more than the middle-income earners.
3. Customers don't often return purchased items, and Customer Satisfaction,
   It is highly affected by brand loyalty.
4. Customers are very sensitive to discounts, and Customers  with high income are interested in discounts
5. Customers who purchase a particular product, like Home Appliances, Animal feed, use Standard Shipping,
   Electronics and Sport & Outdoor have no preference, Gardening & Outdoor and Office supply prefer express shipping.
6. Social media Influence is highly affected by product purchase and product rating
7. The product category with the highest return rate is  Jewelry & accessories and Electronics
   
## Recommendation Report
1. Tailor marketing  strategies toward young customers with trendy products like S/w & Apps, outdoors & gardening,
while older customers with toys & games and electronics.
2. Improve customer satisfaction through better product descriptions and post-purchase support to reduce product returns.
3. Do a discount campaign and focus more on middle-income shoppers, and introduce exclusive offers to high-income shoppers.
4. Offer free shipping for high-value and large quantities of products purchased by customers.
5. Invest more in social media campaigns for visually appealing products to target more customers for better engagement.
6. Include detailed, clear quality descriptions for all products to minimize return rate.

