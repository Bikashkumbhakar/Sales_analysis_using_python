# Sales_analysis_using_python

Overview
This project involves analyzing a large sales dataset to extract valuable insights. The goal is to explore sales trends over time, identify the best-selling products, and create visualizations to present the findings effectively. The dashboard created using Dash by Plotly provides an interactive way to explore these insights.

Features
Sales Trends Over Time: Visualize monthly, daily, and hourly sales trends.
Best-Selling Products: Identify top products by quantity sold and total sales.
Interactive Visualizations: Explore data through interactive bar charts, line charts, and pie charts.
Dataset
The dataset includes the following columns:

Order Date: Date and time when the order was placed.
Quantity Ordered: Quantity of products ordered.
Price Each: Price of each product.
Sales: Total sales amount (Quantity Ordered * Price Each).
Product: Name of the product.
City: City where the order was placed.
Visualizations
Total Sales by Month: A bar chart showing the total sales for each month.
Total Sales by Day: A line chart showing the total sales for each day of the month.
Total Sales by Hour: A bar chart showing the total sales for each hour of the day.
Sales Distribution by Hour: A pie chart showing the distribution of sales across different hours of the day.
Top Products by Quantity Sold: A bar chart showing the top products based on the quantity sold.
Top Products by Total Sales: A bar chart showing the top products based on total sales amount.
Setup Instructions
Clone the Repository:

sh
Copy code
git clone https://github.com/yourusername/sales-data-analysis-dashboard.git
cd sales-data-analysis-dashboard
Install Dependencies:
Make sure you have pip and virtualenv installed. Create a virtual environment and activate it:

sh
Copy code
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
Install the required Python packages:

sh
Copy code
pip install dash pandas plotly
Prepare the Data:
Ensure your dataset (Sales Data.csv) is in the project directory.

Run the Dashboard:
Execute the following command to start the Dash app:

sh
Copy code
python app.py
Open your web browser and navigate to http://127.0.0.1:8050 to view the dashboard.

Usage
Exploring Sales Trends: Use the interactive bar and line charts to observe how sales vary across different months, days, and hours.
Identifying Best-Selling Products: Use the bar charts to see which products are the best-sellers in terms of quantity and total sales amount.
Analyzing Sales Distribution: Use the pie chart to understand how sales are distributed across different hours of the day.
