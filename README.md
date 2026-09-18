📊 Sales Performance Dashboard

📌 Project Overview

The Sales Performance Dashboard is an interactive data visualization project developed using Python, Streamlit, Pandas, and Plotly.

The dashboard helps users analyze sales performance through key performance indicators, filters, charts, and product-level analysis.

🚀 Features

- 📈 Monthly Sales Trend
- 💰 Total Sales
- 💵 Total Profit
- 🛒 Total Orders
- 📊 Profit Margin
- 🌍 Sales by Region
- 🏷️ Sales by Category
- 🏆 Top 10 Products
- 🔍 Region Filter
- 🔍 Category Filter

🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- Plotly
- CSV Dataset

📂 Project Structure

Sales-Performance-Dashboard/
│
├── app.py
├── sales_data.csv
├── requirements.txt
└── README.md

📊 Dashboard KPIs

The dashboard displays:

- Total Sales – Sum of all sales
- Total Profit – Sum of all profits
- Total Orders – Number of unique orders
- Profit Margin – Profit as a percentage of total sales

The uploaded project calculates these KPIs directly from the sales dataset.

🔍 Filters

Users can filter the dashboard based on:

1. Region
2. Category

The charts and product analysis update according to the selected filters.

📈 Visualizations

Monthly Sales Trend

A line chart is used to display monthly sales performance.

Sales by Region

A bar chart displays sales performance across different regions.

Sales by Category

A pie chart shows the distribution of sales across product categories.

Top 10 Products

The dashboard identifies the top 10 products based on total sales.

📦 Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/Sales-Performance-Dashboard.git

Open the project folder:

cd Sales-Performance-Dashboard

Install the required libraries:

pip install -r requirements.txt

▶️ Run the Dashboard

Run the following command:

streamlit run app.py

The dashboard will open in your web browser.

📄 Dataset

The dashboard loads the dataset from:

sales_data.csv

The dataset should contain columns such as:

Date
Sales
Profit
Order_ID
Region
Category
Product

The application reads the CSV file and converts the "Date" column into a date format.

🎯 Objective

The main objective of this project is to provide an easy-to-use interactive dashboard for analyzing sales performance and identifying important sales trends.

👨‍💻 Author

Raha sekaran

---

⭐ If you find this project useful, consider giving it a star!
