# Swiggy-EDA
📌 Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on a dataset derived from Swiggy, India’s leading online food delivery platform. The goal is to uncover insights about restaurant performance, delivery patterns, customer preferences, and geographic trends to guide data-driven decisions.

🎯 Key Objectives
Analyze restaurant performance by city and area

Study distribution of food prices, delivery times, and customer ratings

Identify top-performing and underperforming restaurants and areas

Explore ordering behavior by food type

Visualize trends and patterns using histograms, scatter plots, KDEs, box plots, and bar charts

📊 Key Insights
Most restaurants are located in Kolkata, followed by Mumbai

Top 5 food types: Indian > Chinese > North Indian > Fast Food > South Indian
(Least ordered: Beverages)

Most frequent price points: ₹200 and ₹300

Top 5 areas by rating:
Girish Park, Vardhman Premium Mall, Ekdalia, Santacruz Bandra East, Wallace Garden

Bottom 5 areas by rating:
Kausar Baugh NIBM Road, Punjab Bagh, Shakurpur, Dapodi, Dhanakawadi

Top 5 restaurants by rating:
La Pino'z Pizza, Nic Natural Ice Creams, Baskin Robbins, Subway, KFC

Bottom 5 restaurants by rating:
Maggi Bowl, Jannath Chicken, Urban Foods Ambawadi, Down Town House, Cia Chinese

📈 Visualizations
📌 Scatter Plots show most ratings between 3.5–4.5, and prices between ₹100–₹500

🔺 Regression Plot: Slight positive trend — higher price may slightly relate to higher rating, but with high variability

📦 Histograms: Most deliveries fall in 35–60 mins, with mode at 45 mins

🔁 KDE Plots: Suggest two delivery patterns — quick-service and full-service

📍 City Comparison:

Mumbai & Hyderabad: Fastest & consistent

Kolkata: Longest delivery times

Surat & Ahmedabad: Tend to deliver faster

⚙️ Tools Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📌 Conclusion
This EDA highlights valuable trends in customer behavior, restaurant performance, and delivery operations. The analysis reveals that while price and rating show a weak correlation, geography and restaurant type play a major role in influencing delivery time and customer satisfaction.
