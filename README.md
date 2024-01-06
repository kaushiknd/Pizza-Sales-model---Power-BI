# Pizza Sales Model - Power Bi
## Introduction
Embarking on a journey to enhance the success of Domino's Pizza Outlet in bustling Mumbai, we present a comprehensive Power BI report that serves as a strategic compass for unlocking actionable insights. In the realm of delectable pizza offerings and customer satisfaction, this report delves into the heart of operational efficiency, customer preferences, and sales performance. By leveraging the power of data, we aim to uncover key trends that will not only elevate sales but also redefine the culinary experience for our patrons.

## Objective
The primary objective of this Power BI report is to unveil invaluable insights that empower the Domino's Pizza Outlet in Mumbai to take informed actions towards increasing sales and refining operational efficiency. By analyzing trends in pizza orders, understanding customer preferences, and evaluating sales performance, our goal is to offer actionable recommendations. Through this analysis, we aim to optimize the menu, pricing strategies, and promotional activities, ensuring a delightful experience for our customers and sustained success for the outlet in the competitive Mumbai market.

### Data: 
__pizza_sale.xlsx__ -: The data set contains information on Domino’s Pizza Sales order details in the Mumbai outlet.  This dataset contains four tables order_details, pizza_types, pizzas & orders

### Data Dictionary:
- **order_details_id**: Each order placed by a table
- **order_id**: Each pizza placed within each order
- **pizza_id**: Pizza ordered with its size
- **quantity**: Quantity ordered for each pizza
- **pizza_type_id**: Pizza ordered with its Category(vz-Veg Pizza & nvz- Non Veg Pizza
- **Name**: Name of the Pizza ordered
- **Category**: Type of product available i.e. Veg pizza, Non-Veg pizza, bread, cake parcel, pasta, etc.
- **Size**: Size of Pizza (Large, Medium, Regular)
- **Price**: Cost of each Pizza
- **date**: Date of Oder Placed
- **time**: Time of Order Placed

## Data Cleaning and Manipulation Overview:
### **1. Handling Header in pizza_types Table:**

- The initial row, which served as the header in the pizza_types table, was appropriately addressed to ensure accurate data representation.

### **2. Standardizing Time Data in orders Table:**

- Recognizing inconsistencies in the Time column of the orders table, the data type was modified to accurately reflect time. This enhancement contributes to the overall consistency and reliability of the dataset.

### **3. Adjusting Data Type in pizzas Table:**

- The price column in the pizzas table underwent a modification in data type, aligning it with the appropriate numerical format for consistent and accurate calculations.

### **4. Power Query Loading:**

- The tables were efficiently loaded using Power Query, a crucial step in preparing the dataset for subsequent analyses.

### **5. Additional Columns and Measures:**

- **Total Sales Calculation in order_details Table:**
    - A Total Sales column was introduced in the order_details table, computed using a DAX formula that multiplies the quantity by the corresponding pizza price.
- **Day Column in orders Table:**
    - A Day column was introduced in the orders table, providing a formatted representation of the day corresponding to each order date.
- **Average Order Price Measure in pizza Table:**
    - A new measure, Average Order Price, was created for the pizza table. This measure offers insights into the average price of orders, facilitating strategic pricing decisions.

## Key Points:
- **Enhanced Data Consistency:**
    - Measures were taken to standardize and improve the consistency of the dataset, addressing header issues and ensuring uniform data types.
- **Time Data Accuracy:**
    - Correcting inconsistencies in the Time column of the orders table enhances the accuracy of time-related analyses and reporting.
- **Numeric Data Precision:**
    - Adjusting the data type of the price column in the pizzas table ensures precise numerical calculations for comprehensive analysis.
- **Strategic Measures and Columns:**
    - Introduction of calculated columns and measures, such as Total Sales, Day, and Average Order Price, equips the dataset with valuable metrics for in-depth analysis and decision-making.

These steps lay the foundation for a robust and accurate analysis of the Domino's Pizza Outlet data, offering actionable insights for optimizing sales and operational efficiency.

## Questions according to the above parameters:

1. What days and Times are the busiest?
2. What are the best and worst-selling pizzas based on price and quantity?
3. Which flavor is Best bought?
4. What are the popular pizzas in Veg and Non-Veg
5. Which size of Pizzas are mostly bought?
6. What days are preferred popularly i.e. Weekdays or Weekend?
7. What are the popular other categories preferred?
8. What is the Growth in a Year?

## Dashboard:

![image](https://github.com/kaushiknd/Pizza-Sales-model---Power-BI/assets/115521614/d2021b33-2ba1-4887-ad08-6b993efcadf2)


## Recommendations:

1. **Strategic Focus on Weekends:**
    - Capitalize on increased order volumes observed on Sundays and Saturdays. Consider targeted promotions or special offers during weekends to further boost sales.
2. **Optimal Timing for Promotions:**
    - Recognize the peak ordering period between 6 to 7 pm. Strategically plan marketing campaigns or promotions during this time to maximize customer engagement.
3. **Product Portfolio Enhancement:**
    - Given the popularity of Veg and Non-Veg pizzas, consider expanding the variety within these categories. Introduce new flavors or variations to cater to diverse customer preferences.
4. **Promote Best-Selling Veg Pizzas:**
    - Highlight and promote the top three most favorable Veg pizzas - Fresh Vegie, Double Cheese Margherita, and Cheese and Corn. Leverage marketing strategies to enhance visibility and sales for these popular choices.
5. **Revise Non-Performing Veg Pizzas:**
    - Evaluate the recipes and marketing approach for the least popular Veg pizzas - Peppy Paneer, Paneer Makhani, and Moroccan Spice Pasta Pizza. Consider repositioning or discontinuing these items based on customer feedback.
6. **Emphasize Top Non-Veg Choices:**
    - Promote the top three most favorable Non-Veg pizzas - Chicken Golden Delight, Chicken Pepperoni, and Pepper Barbecue Chicken. Implement targeted promotions to further elevate these best-sellers.
7. **Address Low-Performing Non-Veg Pizzas:**
    - Investigate the reasons behind the underperformance of Chicken Sausage, Moroccan Spice Pasta Pizza, and Creamy Tomato Pasta Pizza. Implement changes in recipes, marketing, or pricing as needed.
8. **Optimize Size and Pricing:**
    - Given that most products are ordered in regular-sized pizzas with an average order price of Rs 193.92, consider adjusting the pricing strategy for other sizes and exploring bundle offerings to encourage larger orders.
9. **Seasonal Sales Considerations:**
    - Acknowledge the fluctuating demand throughout the year. Plan marketing initiatives around the observed trends, ensuring that promotions and product launches align with periods of higher customer engagement.

By strategically addressing these insights, we can enhance customer satisfaction, optimize our product offerings, and drive overall sales growth. I look forward to implementing these recommendations for continued success.
