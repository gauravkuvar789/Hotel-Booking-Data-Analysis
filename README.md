# Hotel-Booking-Data-Analysis
Data analytics project using Python and Power BI to analyze hotel booking data, uncover cancellation patterns, and provide insights to improve revenue and customer retention.

#Hotel Booking Data Analysis

#Overview
This project covers the complete data analytics workflow — from raw data to actionable insights. It includes data cleaning and transformation in Power BI Query Editor, exploratory data analysis (EDA) in Python, and interactive dashboard creation in Power BI.
The goal is to understand hotel booking patterns, cancellation behavior, and identify factors influencing revenue and customer satisfaction for both City and Resort Hotels.

#Dataset
File Name: hotel_bookings.csv
Original Size: 119,390 rows × 32 columns
Final Size (after cleaning): ~89,000 rows
Format: CSV
Description: Contains hotel booking details such as hotel type, arrival dates, customer type, lead time, country, ADR (Average Daily Rate), and cancellation status.
Objective: Discover insights that can help hotels reduce cancellations, improve occupancy rates, and enhance pricing strategies.

#Tools & Technologies
Python (VS Code): Pandas, NumPy, Matplotlib, Seaborn
Power BI: Query Editor (data cleaning) and Dashboard Creation
Reporting: Gamma (summary & presentation)

#Project Steps
Data Cleaning (Power BI Query Editor):
Imported the raw dataset into Power BI.
Removed null values and duplicate records.
Standardized data types (e.g., dates, numbers, text fields).
After cleaning, approximately 89,000 valid records remained for analysis.

Exploratory Data Analysis (Python):
Loaded the cleaned data for further analysis.
Explored trends such as booking patterns, cancellations, and pricing distribution.
Used Matplotlib and Seaborn for visual exploration and trend detection.

Dashboard Creation (Power BI):

Built an interactive dashboard to visualize key performance metrics:
Total Bookings and Cancellations
Revenue by Hotel Type and Month
ADR (Average Daily Rate) Trends
Bookings by Country and Customer Type
Cancellation Rate Comparison between City and Resort Hotels

Report (Gamma):
Created a clean and structured presentation summarizing the findings and business recommendations.

Results & Insights

City Hotels received higher booking volumes but had a 40% cancellation rate.
Higher prices (ADR) correlated with an increased likelihood of cancellations.
Resort Hotels showed strong seasonality with peak bookings during June–August.
Guests booking well in advance (long lead time) were more prone to cancel.
Implementing flexible pricing and targeted offers could reduce cancellations by 15–20% and improve revenue stability.

#How to Run
Open the project folder in VS Code.
Run the Python notebook/script to analyze data and generate charts.
Open the Power BI Dashboard (.pbix) file to explore visual insights.
Review the Gamma presentation for a summarized business report.

Deliverables
Cleaned dataset – hotel_bookings_cleaned.csv
Python notebook / script – hotel_booking_analysis.ipynb
Power BI Dashboard – Hotel_Booking_Dashboard.pbix
Gamma Report / Presentation – Hotel_Booking_Insights_Report

Conclusion
This project demonstrates strong data analytics and visualization skills, combining Python for analysis and Power BI for storytelling.
It highlights how data cleaning, EDA, and visualization can transform raw booking data into valuable business insights for the hospitality industry.
