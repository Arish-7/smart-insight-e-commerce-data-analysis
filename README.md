# E-Commerce Sales Dashboard

An interactive E-Commerce Analytics Dashboard built using Python, Streamlit, and MySQL to analyze sales performance, product trends, and business insights.

---

## Overview

This project provides a complete visualization of e-commerce sales data. It enables users to track revenue, analyze product performance, and explore transaction details through an interactive dashboard interface.

---

## Features

### Key Metrics
- Total Revenue
- Total Orders
- Average Basket Size

### Visualizations
- Monthly Sales Trend (Line Chart)
- Product Revenue Share (Pie Chart)
- Sales Heatmap

### Interactivity
- Filter data by Month and Product
- View detailed transaction data
- Drill-down analysis by product

### Insights
- Identify top-selling products
- Analyze monthly performance trends
- Understand revenue distribution

---

## Tech Stack

- Frontend: Streamlit
- Backend: Python
- Database: MySQL
- Libraries: Pandas, Matplotlib, Plotly, SQLAlchemy, PyMySQL

---

## Project Structure

E-Commerce-Dashboard/
│
├── ecommerce_dashboard.py
├── ecommerce.py
├── tempCodeRunnerFile.py
└── README.md

---

## Installation and Setup

### 1. Clone the Repository

git clone https://github.com/your-username/ecommerce-dashboard.git
cd ecommerce-dashboard

### 2. Install Dependencies

pip install streamlit sqlalchemy pymysql pandas matplotlib plotly

### 3. Configure MySQL Database

Create a database:

CREATE DATABASE ecommercedb;

Create required tables:
- Transaction
- TransactionProduct
- Product

Update database credentials in your code:

user = "root"
password = "TIGER"
host = "localhost"
database = "ecommercedb"

---

## Running the Application

streamlit run ecommerce_dashboard.py

Open your browser and go to:

http://localhost:8501

---

## How It Works

- Fetches data from the MySQL database
- Processes data using Pandas
- Computes key performance indicators (KPIs)
- Generates visualizations using Plotly and Matplotlib
- Displays an interactive dashboard via Streamlit

---

## Use Cases

- Business analytics dashboard
- Sales performance tracking
- Data visualization learning
- Portfolio project

---

## Future Enhancements

- Machine learning-based sales prediction
- Customer segmentation
- Cloud deployment (Streamlit Cloud or AWS)
- Real-time data updates

---

## Author

Arish  
AI & ML Student  

---

## Support

If you find this project useful:

- Star the repository
- Fork it
- Share it

---

## Contact

Feel free to connect for collaboration or feedback.

---

## Tags

Python, Streamlit, MySQL, DataAnalytics, DataVisualization, Dashboard, MachineLearning, AI, OpenSource, BusinessIntelligence
