Introduction
This Case study has been taken from Maven analytics. The fictitious pizza place, has dataset including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.

About the Data We are given 4 data sheets in csv that are imported in SQL via Import Wizard
1.	orders.csv has columns: order_id, date, time
2.	order_details.csv has columns: order_details_id, order_id, pizza_id, quantity
3.	pizza_types.csv has columns: pizza_type_id, name, category, ingredients
4.	pizzas.csv has columns: pizza_id, pizza_type_id, size, price


 1. Data Collection and Acquisition
1. 1 Data Source and Structure
I got this dataset from Kaggle, the data contains the 12 columns namely; order_id, order_details_id, pizza_id, quantity, order_date, order_time, unit_price, total_price, pizza_size, pizza_category, pizza_ingredients, pizza_name.

1.2 Tool
We’ll utilize Microsoft SQL Server(MS SQL Server) as our primary data tool for the process of data cleaning, analysis.

1.3 Data Dictionary
The data dictionary speaks extensively on the meaning of the dataset and what it entails. This pizza sales dataset make up 12 relevant features:
•	order_id: Unique identifier for each order placed by a table
•	order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
•	pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price
•	quantity: Quantity ordered for each pizza of the same type and size
•	order_date: Date the order was placed (entered into the system prior to cooking & serving)
•	order_time: Time the order was placed (entered into the system prior to cooking & serving)
•	unit_price: Price of the pizza in USD
•	total_price: unit_price * quantity
•	pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)
•	pizza_category: Unique key identifier that ties the pizza ordered to its details, like size and price
•	pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)
•	pizza_name: Name of the pizza as shown in the menu




