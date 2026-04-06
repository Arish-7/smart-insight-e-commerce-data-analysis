🛒 E-Commerce Sales Dashboard

An interactive E-Commerce Analytics Dashboard built using Python, Streamlit, and MySQL to analyze sales performance, product trends, and business insights.

📌 Overview

This project provides a complete visualization of e-commerce sales data. It helps track revenue, analyze product performance, and explore transaction details using an interactive dashboard.

🚀 Features
📊 Key Metrics
Total Revenue
Total Orders
Average Basket Size
📈 Visualizations
Monthly Sales Trend (Line Chart)
Product Revenue Share (Pie Chart)
Sales Heatmap
🎯 Interactivity
Filter by Month and Product
View transaction data
Drill-down by product
🏆 Insights
Top-selling products
Monthly performance trends
Revenue distribution
🧰 Tech Stack
Frontend: Streamlit
Backend: Python
Database: MySQL
Libraries: Pandas, Matplotlib, Plotly, SQLAlchemy, PyMySQL
📂 Project Structure
E-Commerce-Dashboard/
│
├── ecommerce_dashboard.py
├── ecommerce.py
├── tempCodeRunnerFile.py
└── README.md
⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/ecommerce-dashboard.git
cd ecommerce-dashboard
2. Install Dependencies
pip install streamlit sqlalchemy pymysql pandas matplotlib plotly
3. Configure MySQL Database

Create a database:

ecommercedb

Required tables:

Transaction
TransactionProduct
Product

Update credentials in the code:

user = "root"
password = "TIGER"
host = "localhost"
database = "ecommercedb"
▶️ Run the Application
streamlit run ecommerce_dashboard.py

Open in browser:

http://localhost:8501
📊 How It Works
Fetches data from MySQL database
Processes data using Pandas
Calculates KPIs
Generates visualizations
Displays interactive dashboard via Streamlit
💡 Use Cases
Business analytics dashboard
Sales performance tracking
Data visualization practice
Portfolio project
🔮 Future Enhancements
Machine learning-based sales prediction
Customer segmentation
Cloud deployment (Streamlit Cloud / AWS)
Real-time data updates
🧑‍💻 Author

Arish
AI & ML Student

⭐ Support

If you like this project:

Star the repository
Fork it
Share it
📬 Contact

Feel free to connect for collaboration or feedback.

🔖 Tags

#Python #Streamlit #MySQL #DataAnalytics #DataVisualization #Dashboard #MachineLearning #AI #StudentProject #GitHubProjects #OpenSource #Analytics #BusinessIntelligence #PortfolioProject

🔥 Tip

After pasting:

Click Preview tab in GitHub
Then click Commit changes
