**# Pizza_Sales_Sql**

**Description:**
  This project analyzes pizza sales data to uncover insights into customer preferences, sales performance and revenue trends. Using SQL, it explores order volumes, popular pizza types and sizes, and peak ordering times. The analysis also highlights top revenue generating items and category-wise performance. These insights support smarter decisions in marketing, inventory, and menu planning.

**Dataset Description:**
1. orders.csv : Contains order-level data including order_id, date and time of purchase.
2. order_details.csv : Line-item details for each order, with order_details_id, order_id, pizza_id and quantity.
3. pizzas.csv : Provides price and size details for each pizza, with fields like pizza_id, pizza_type_id, size and price.
4. pizza_types.csv : Describes the types of pizzas, including pizza_type_id, name, category(e.g., classic, veggie, chicken), and ingredients.

**Analysis Tasks:**
1. Retrieve the total number of orders placed.
2. Calculate the total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types along with their quantities.
6. Join the necessary tables to find the total quantity of each pizza category ordered.
7. Determine the distribution of orders by hour of the day.
8. Join relevant tables to find the category-wise distribution of pizzas.
9. Group the orders by date and calculate the average number of pizzas ordered per day.
10. Determine the top 3 most ordered pizza types based on revenue.
11. Calculate the percentage contribution of each pizza type to total revenue.
12. Analyze the cumulative revenue generated over time.
13. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

**Conclusion:**
- Over $817,000 in revenue was generated from more than 21,000 customer orders.
- Large-sized pizzas were the most frequently ordered size.
- The classic deluxe and BBQ chicken pizzas were the top selling and most profitable items.
- Most orders were placed during lunch and dinner hours, highlighting peak business times.
- A few pizzas contributed to the majority of revenue, supporting the 80/20 rule in menu performance.
