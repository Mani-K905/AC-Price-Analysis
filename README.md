🧊 AC Price Analysis using Flipkart Data
📘 Project Overview
This project, “AC Price Analysis using Web Scraping and Pandas,” focuses on extracting and analyzing air conditioner (AC) data from Flipkart to identify pricing patterns, brand comparisons, and seasonal trends.
We use Python for web scraping, data cleaning, and visualization to uncover market insights and consumer preferences.

👩‍💻 About Us
We are a team of B.Tech graduates in Electronics and Communication Engineering (ECE) and aspiring data analysts passionate about turning raw data into insights.

Team Members:

- Mani K – LinkedIn

🧠 Business Problem
Consumers often face challenges in selecting the right AC due to varying brands, prices, and features.
Retailers and marketers also need pricing trend insights to stay competitive.
The AC market is dynamic and seasonally influenced, making data-driven analysis crucial.

🎯 Objectives
Scrape real-time AC data from Flipkart using Python.
Analyze pricing trends across different brands, capacities, and features (e.g., star rating, inverter type).
Visualize findings using Pandas, Matplotlib, and Seaborn.
Derive data-driven insights on market behavior and consumer preferences.
🧰 Tools & Technologies Used
Category	Tools / Libraries
Programming & Analysis	Python, Pandas, NumPy
Web Scraping	BeautifulSoup, Requests, re (Regex)
Visualization	Matplotlib, Seaborn
📊 Data Collection (Web Scraping)
Source: Flipkart (AC listings: price, brand, model, capacity, star rating, inverter type)

Process:

Send HTTP requests to Flipkart pages.
Parse HTML content using BeautifulSoup.
Extract relevant features and store in a structured CSV/Excel dataset.
Challenges:

Dynamic website content & pagination
Missing/inconsistent data
Avoiding IP blocking during scraping
🧹 Data Cleaning & Preprocessing
Handled missing values by replacing or removing incomplete entries.
Converted data types (Price → numeric, Star Rating → integer).
Removed duplicates to ensure data integrity.
Standardized features (brand names, inverter type, etc.)
Final dataset columns:
Brand | Model | Price | Capacity | Star_Rating | Inverter | Units | Room_Size | AI
📈 Exploratory Data Analysis (EDA)
Performed various analyses and visualizations:

Statistical Summary: Mean, median, mode of prices.
Price Distribution: Bar plots showing overall price range.
Brand-wise Price & Power Comparison
Capacity vs. Price correlation (≈ +0.7 linear trend).
AI, Star Rating, and Area-based comparisons
🔍 Key Insights
1.0-ton 3-star inverter ACs dominate the market.
Voltas and MarQ lead the budget segment (<₹25k).
LG and Samsung dominate the premium market (>₹32k).
Midea offers mid-range pricing with AI and inverter features.
Clear correlation between capacity and price.
❓ Key Questions Explored
Which brands offer the best value for money?
How do features (capacity, inverter, star rating) affect pricing?
What seasonal trends influence AC prices?
🙏 Acknowledgment
Special thanks to all open-source contributors and the Flipkart platform for enabling data accessibility for analysis.

🏁 Conclusion
This project demonstrates how Python-based data analysis and web scraping can help extract market insights from real-world e-commerce data — valuable for both consumers and marketers.
