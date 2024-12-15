# Pizza_Sales

## Project Overview
This project analyzes and visualizes key indicators of our pizza sales data to gain insights into business performance. By examining various metrics and trends, we can better understand customer preferences, identify peak sales periods, and evaluate the performance of different pizza categories and sizes.

## Technologies Used
- **SQL**: Used for data extraction, transformation, and analysis.
- **Power BI**: Used for creating interactive dashboards and visualizations.

## Problem Statement
We need to analyze key indicators for our pizza sales data to gain insights into our business performance. Specifically, we want to calculate the following metrics:

1. **Total Revenue**: The sum of the total prices of all pizza orders.
2. **Average Order Value**: The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
3. **Total Pizzas Sold**: The sum of the quantities of all pizzas sold.
4. **Total Orders**: The total number of orders placed.
5. **Average Pizzas Per Order**: The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.

## Charts Requirement
We would like to visualize various aspects of our pizza sales to gain insights and understand key trends. We have identified the following requirements for creating charts:

1. **Daily Trend for Total Orders**: Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help us identify any patterns or fluctuations in order volumes on a daily basis.
2. **Monthly Trend for Total Orders**: Create a line chart that illustrates the monthly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high order activity.
3. **Percentage of Sales by Pizza Category**: Create a pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.
4. **Percentage of Sales by Pizza Size**: Generate a pie chart that represents sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.
5. **Total Pizzas Sold by Pizza Category**: Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.
6. **Top 5 Pizza Sellers by Revenue, Total Quantity, and Total Orders**: Identify the top 5 pizza sellers based on revenue, total quantity sold, and total orders.

## Folder Structure
- **sql_queries/**: Contains SQL scripts used for data analysis.
- **data/**: Contains the raw data files.
- **docs/**: Contains additional documentation and reports.
- **README.md**: Project overview and instructions.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pizza_sales.git


SQL Queries
The SQL queries used in this project are located in the sql_queries folder. Each script is designed to extract specific insights from the data.

Data
The data files used for analysis are located in the data folder. Ensure you have the necessary permissions to access and use these files.

Documentation
Additional documentation and reports are available in the docs folder.

Visualizations
The Power BI dashboards created for this project provide interactive visualizations of the analysis results. These dashboards include:

Sales Performance Dashboard: Visualizes overall sales trends, top-selling products, and sales by region.
Customer Insights Dashboard: Analyzes customer demographics, purchase behavior, and customer segmentation.
Operational Efficiency Dashboard: Tracks inventory levels, order fulfillment times, and supply chain performance.
For more detailed information, please refer to the documentation in the docs folder.

Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.




## Pizza Sales Dashboard Insights

### Overview
Welcome to the Pizza Sales Dashboard! This dashboard provides an in-depth analysis of our pizza sales, helping us to track performance, understand customer preferences, and make data-driven decisions to enhance our business. Below, you'll find detailed insights into each key metric and visualization displayed on our dashboards.



- *Description*: This visualization displays the total revenue generated from our pizza sales. 

![Screenshot 2024-10-19 232229 - Copy](https://github.com/user-attachments/assets/8a908195-0243-4fc5-8f58-2c0fc6efdc25)

- *Insight*: The current total revenue stands at **817.86K*, showcasing the financial performance of our business. Monitoring this metric helps us assess the overall health of our sales operations and identify trends over time.

Avg Order Value

- *Description*: This visualization shows the average amount spent per order.

![Screenshot 2024-10-19 232338 - Copy](https://github.com/user-attachments/assets/5754a4f6-8ec5-432d-bd52-9194bd30a658)

- *Insight*: The average order value is **38.31*. Understanding this metric is crucial for assessing customer spending behavior. It helps us strategize on how to increase the average order value through upselling and promotional activities.

Total Pizzas Sold

- *Description*: This visualization displays the total number of pizzas sold.

![Screenshot 2024-10-19 232407 - Copy](https://github.com/user-attachments/assets/4be5db62-9766-48f6-8d70-c6d3600b2f61)

- *Insight*: The total number of pizzas sold is **49,574*. This metric highlights the overall sales volume and helps us gauge the popularity of our pizza offerings. Tracking this figure over time allows us to identify trends and make informed decisions about inventory and promotions.

Total Orders

- *Description*: This dashboard visualization displays the total number of orders processed.

![Screenshot 2024-10-19 232429 - Copy](https://github.com/user-attachments/assets/4e7cbc2e-4e9d-4d08-a570-e1700efbdc7c)

- *Insight*: The total number of orders is **21350*, indicating the volume of transactions handled. Monitoring this metric helps us understand our pizza offerings' overall demand and customer engagement.

Avg Pizzas Per Order

- *Description*: This visualization shows the average number of pizzas ordered per transaction.

![Screenshot 2024-11-07 205542](https://github.com/user-attachments/assets/9fd22bd3-7e5a-4c41-ba96-0031e1285554)

- *Insight*: The average number of pizzas per order is **2.32*. This metric helps us gauge customer buying behavior and the typical size of an order. It can also inform our promotions and marketing strategies to encourage higher order volumes.

Daily Trend for Total Orders

- *Description*: This bar chart illustrates the daily trend for total pizza orders throughout the week.

![Screenshot 2024-10-25 223158 - Copy](https://github.com/user-attachments/assets/e80a574d-ea2c-4b4f-8898-20ed10e32780)

- *Insight*: 
  - *Sunday*: 2.6K orders
  - *Monday*: 2.8K orders
  - *Tuesday*: 3.0K orders
  - *Wednesday*: 3.0K orders
  - *Thursday*: 3.2K orders
  - *Friday*: 3.5K orders (highest)
  - *Saturday*: 3.2K orders

  This visualization represents how orders fluctuate during the week. Notably, Friday has the highest number of orders at 3.5K, indicating a peak in demand likely due to the start of the weekend. In contrast, Sunday shows the lowest order volume at 2.6K, suggesting a potential area to explore for sales promotions or marketing efforts to boost orders on this day.

Monthly Trend for Total Orders

- *Description*: This line graph illustrates the monthly trend for total pizza orders from January to December. Each data point represents the total number of orders for that month.

![Screenshot 2024-10-25 223245 - Copy](https://github.com/user-attachments/assets/cba3956b-642a-4faf-854f-1dc694404094)

- *Insight*:
  - *January*: 1845 orders
  - *February*: 1685 orders
  - *March*: 1840 orders
  - *April*: 1799 orders
  - *May*: 1853 orders
  - *June*: 1773 orders
  - *July*: 1935 orders (highest)
  - *August*: 1841 orders
  - *September*: 1661 orders (lowest)
  - *October*: 1646 orders
  - *November*: 1792 orders
  - *December*: 1680 orders

  This visualization provides a clear representation of how orders fluctuate throughout the year. Notably, July had the highest number of orders in 1935, possibly due to summer holidays and events. In contrast, September shows the lowest order volume at 1661, suggesting a potential opportunity to boost sales during this month through targeted promotions or marketing efforts.

Percent of Sales by Pizza Category

- *Description*: This pie chart shows the percentage distribution of sales by pizza category. The chart is divided into four segments, each representing a different pizza category.

![Screenshot 2024-10-25 223322](https://github.com/user-attachments/assets/9bbe334e-af1c-42b9-a358-db0c0820b513)

- *Insight*: 
  - *Classic*: 26.91%
  - *Supreme*: 25.46%
  - *Chicken*: 23.96%
  - *Veggie*: 23.68%

  The chart reveals that the *Classic* pizza category leads with the highest sales percentage at *26.91%, followed closely by **Supreme* at *25.46%. **Chicken* and *Veggie* categories also contribute significantly, with *23.96%* and *23.68%* respectively. This information is valuable for understanding customer preferences and can inform inventory management and promotional strategies

Percent of Sales by Pizza Size

- *Description*: This pie chart shows the percentage distribution of sales by pizza size. Each size is represented by a different color, making it easy to distinguish between them.

![Screenshot 2024-10-25 223427](https://github.com/user-attachments/assets/0f7cf776-e57f-46e8-8580-11b68e603db3)

- *Insight*: 
  - *Large (45.89%)*: The largest segment of sales comes from the Large size, indicating it is the most popular choice among customers.
  - *Medium (30.49%)*: The Medium size also contributes significantly to sales, showing a strong preference for mid-sized pizzas.
  - *Regular (21.77%)*: Regular-sized pizzas have a smaller but still substantial share of sales.
  - *X-Large (1.72%)*: X-Large pizzas have a minimal share, suggesting they are less popular or ordered infrequently.
  - *XX-Large (0.12%)*: The XX-Large size has the smallest share, indicating it is rarely chosen by customers.

Total Pizzas Sold by pizza_category

- *Description*: This bar chart shows the total number of pizzas sold in four different categories: Classic, Supreme, Veggie, and Chicken.

![Screenshot 2024-10-25 223528](https://github.com/user-attachments/assets/e0de8ca9-94a6-4b3e-a65e-a1fdf689799d)

- *Insight*:
  - *Classic*: 14,888 pizzas sold
  - *Supreme*: 11,987 pizzas sold
  - *Veggie*: 11,649 pizzas sold
  - *Chicken*: 11,050 pizzas sold

  The chart reveals that the *Classic* pizza category leads in sales, with 14,888 pizzas sold, making it the most popular choice among customers. The *Supreme* category follows with 11,987 pizzas sold, while *Veggie* and *Chicken* categories have slightly lower sales at 11,649 and 11,050 respectively. Understanding the popularity of different pizza categories helps us tailor our menu and marketing strategies to meet customer preferences and boost sales.

Busiest Days and Times

- *Description*: This section is divided into two parts: "DAYS" and "MONTHLY."

![Screenshot 2024-10-25 223617](https://github.com/user-attachments/assets/32a86cd5-4a94-4451-8f94-b16bf2c39790)

- *Insight*:
  - *Days*: The data indicates that orders are highest on weekends, specifically on Friday and Saturday evenings. This information helps us plan for peak times, ensuring we have sufficient staff and inventory to meet customer demand.
  - *Monthly*: The maximum orders occur in the months of July and January. This trend suggests a seasonal pattern, possibly influenced by holidays, weather, or promotional events. Understanding these patterns enables us to prepare and strategize effectively for these busy periods.

Sales Performance

- *Description*: This section highlights the sales performance based on pizza category and size.

![Screenshot 2024-10-25 223646](https://github.com/user-attachments/assets/ca5c0cb3-f125-4f0f-8fd0-96bef217c57e)

- *Insight*:
  - *Category: The **Classic Category* contributes to the maximum sales and total orders. This indicates that classic pizzas are the most popular among customers and a significant driver of revenue.
  - *Size: The **Large size* pizza contributes to the maximum sales. This suggests that customers prefer larger pizzas, possibly for sharing, which could inform inventory and marketing strategies focused on promoting large pizzas.

Top 5 Pizzas by Revenue

- *Description*: This bar chart highlights the revenue generated by the top five pizzas in our menu.

![Screenshot 2024-10-25 223846](https://github.com/user-attachments/assets/79e87fa6-f9fe-4918-9e78-cc49998dc531)

- *Insight*:
  - *The Thai Chi...: Generated the highest revenue at **40K*.
  - *The Barbecu...: Also brought in **40K*, indicating it's equally popular.
  - *The Californi...: Close behind with **39K* in revenue.
  - *The Classic ...: Contributed **36K* to the total revenue.
  - *The Spicy Ita...: Rounded out the top five with **33K* in revenue.

  This visualization helps us identify the best-selling pizzas and their contribution to overall sales. Knowing which pizzas are top performers can guide inventory management, marketing strategies, and menu planning to maximize revenue.

Bottom 5 Pizzas by Revenue

- *Description*: This bar chart displays the revenue generated by the five lowest-performing pizzas in our menu.

![Screenshot 2024-10-25 223953](https://github.com/user-attachments/assets/a4875d23-2ef9-4b4a-af4e-c6ae42e36ecd)

- *Insight*:
  - *The Spinach ...: Revenue of **15K*.
  - *The Spinach ...: Revenue of **14K*.
  - *The Mediter...: Revenue of **14K*.
  - *The Green G...: Revenue of **13K*.
  - *The Brie Car...: Revenue of **11K*.

This visualization identifies the pizzas that generate the least revenue. Knowing which pizzas are underperforming can help us make informed decisions about menu adjustments, marketing efforts, or potential discontinuation of certain items. 

Top 5 Pizzas by Quantity 

- *Description*: This bar chart titled "Top 5 Pizzas by Quantity" displays the quantities of the top five pizzas sold. Each bar represents a different pizza type and its corresponding quantity sold.

![Screenshot 2024-10-25 223906](https://github.com/user-attachments/assets/c34365ad-b3e7-4402-8333-441a5befb76e)

- *Insight*: 
  - *The Classic ...*: 2.3K units sold.
  - *The Barbecu...*: 2.3K units sold.
  - *The Peppero...*: 2.3K units sold.
  - *The Hawaiia...*: 2.3K units sold.
  - *The Thai Chi...*: 2.2K units sold.

  This chart indicates that "The Classic," "The Barbecue," "The Pepperoni," and "The Hawaiian" pizzas are equally popular, each selling 2.3K units. "The Thai Chicken" follows closely with 2.2K units sold. Understanding the top-selling pizzas helps us focus on maintaining inventory levels and optimizing marketing efforts for these popular choices.

Bottom 5 Pizzas by Quantity 

- *Description*: This bar chart displays the quantity sold of the five least popular pizzas on our menu. Each bar represents a different pizza type and its corresponding quantity sold.

![Screenshot 2024-10-25 224015](https://github.com/user-attachments/assets/a3b4a673-1088-407c-9593-9cac2e5aeb64)

- *Insight*: 
  - *The Soppressata*: 907 units sold
  - *The Spinach*: 895 units sold
  - *The Calabrese*: 880 units sold
  - *The Mediterranean*: 866 units sold
  - *The Brie Caramelized Onion*: 461 units sold

  This chart identifies the pizzas with the lowest sales volumes. "The Soppressata" leads this category with 907 units sold, while "The Brie Caramelized Onion" has the least at 461 units. Understanding which pizzas are the least popular helps us make informed decisions about potential menu adjustments, marketing efforts to boost their sales, or discontinuation if they are not meeting customer preferences.

Top 5 Pizzas by Total Orders

- *Description*: This bar chart displays the top five pizzas based on the total number of orders. Each bar represents a different pizza type and the corresponding order count.

![Screenshot 2024-10-25 224050](https://github.com/user-attachments/assets/9b5002cb-3228-4970-8cda-a7f22e852716)

- *Insight*:
  - *The Classic*: 2.2K orders
  - *The Pepperoni*: 2.1K orders
  - *The Barbecue*: 2.1K orders
  - *The Hawaiian*: 2.1K orders
  - *The Thai Chicken*: 2.1K orders

  This chart reveals that "The Classic" pizza is the most ordered, with 2.2K orders. "The Pepperoni," "The Barbecue," "The Hawaiian," and "The Thai Chicken" pizzas follow closely, each with 2.1K orders. Understanding the popularity of these top-performing pizzas helps us focus on maintaining inventory levels and optimizing marketing efforts to continue driving sales for these favorites.

Bottom 5 Pizzas by Total Orders

- *Description*: This bar chart titled "Bottom 5 Pizzas by Total Orders" displays the total order numbers for the five least popular pizzas in our menu. Each bar represents a different pizza type and its corresponding total orders.

![Screenshot 2024-10-25 224110](https://github.com/user-attachments/assets/10ebc437-084b-4ad9-83e9-265934de4428)

- *Insight*: 
  - *The Chicken ...*: 878 orders
  - *The Spinach ...*: 864 orders
  - *The Calabres...*: 863 orders
  - *The Mediter...*: 845 orders
  - *The Brie Car...*: 452 orders

This chart identifies the pizzas with the lowest number of total orders. "The Chicken ..." has the highest orders among the bottom five with 878, while "The Brie Car..." has the least with 452. Understanding which pizzas are the least ordered helps us make informed decisions about potential menu adjustments, marketing efforts to boost their sales, or discontinuation if they are not meeting customer preferences.

Best Sellers

- *Description*: This chart highlights the top-performing pizzas in three key categories: Revenue, Quantity, and Total Orders.

![Screenshot 2024-10-25 224150](https://github.com/user-attachments/assets/3bc3d08c-7ea5-4983-812d-5c1371bc6189)

- *Insight*:
  - *Revenue*: 
    - *The Thai Chicken Pizza* contributes the highest revenue among all pizza types. Its popularity and premium pricing likely drive its top performance in this category.
  - *Quantity*: 
    - *The Classic Deluxe Pizza* leads in total quantities sold. This indicates it's a customer favorite, possibly due to its classic toppings and wide appeal.
  - *Total Orders*: 
    - *The Classic Deluxe Pizza* also has the highest total orders. This reinforces its popularity and consistent demand among customers.

Understanding which pizzas are top sellers in these categories helps us make informed decisions about inventory management, marketing strategies, and menu planning to maximize revenue and customer satisfaction.

Worst Sellers

- *Description*: This chart titled "Worst Sellers" highlights the performance of a specific pizza, "The Brie Caramelized Onion Pizza," in three key categories: Revenue, Quantity, and Total Orders.

![Screenshot 2024-10-25 224216](https://github.com/user-attachments/assets/71b81c02-1140-4789-8a6f-8f5d6911b39a)

- *Insight*:
  - *Revenue*: 
    - *The Brie Caramelized Onion Pizza* contributes the minimum revenue among all pizza types. This indicates that it is the least popular in terms of generating sales revenue.
  - *Quantity*: 
    - *The Brie Caramelized Onion Pizza* has the lowest total quantities sold. This suggests it is not frequently chosen by customers.
  - *Total Orders*: 
    - *The Brie Caramelized Onion Pizza* also has the lowest total orders. This reinforces its status as the least ordered pizza on the menu.

Understanding which pizzas are underperforming helps us make informed decisions about potential menu adjustments, marketing efforts to boost their sales, or discontinuation if they are not meeting customer preferences.















