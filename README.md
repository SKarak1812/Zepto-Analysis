# Zepto-Analysis
This project analyzes Zepto’s order dataset to uncover insights about delivery performance, customer ratings, category-wise revenue, and city-level trends.
Using Python and Pandas, various KPIs such as delivery duration, top-performing categories, and fee distribution were calculated.

🔧 Technologies Used

Python

Pandas

Jupyter Notebook / Google Colab

Excel (raw dataset)

📁 Key Steps & Insights
1. Loading the Dataset

The Excel file is imported into a Pandas dataframe for analysis.

2. Cleaning & Formatting

Converted Order_Date and Delivery_Time into datetime format to ensure accurate calculations.

3. Delivery Duration Calculation

Calculated delivery time (in minutes) using:

Delivery_Duration = Delivery_Time – Order_Date

4. City-wise Delivery Performance

Grouped data by city to compute average delivery time per city.

5. Category-wise Customer Ratings

Calculated the average customer rating for each product category.

6. Revenue Analysis

Summed total order value per category to identify top revenue-generating categories.

7. Express vs Normal Delivery Comparison

Compared average delivery times of each delivery mode to determine which mode is faster.

8. Delivery Fee Insights

Average delivery fee per category

Total delivery fee collected by each city

9. Top-Selling Category

Ranked categories based on total revenue to identify the best-performing segment.

10. Fastest vs Slowest Categories

Analyzed average delivery duration per category to reveal which categories are delivered fastest and slowest.

📊 What This Project Shows

Delivery efficiency across different cities

Customer satisfaction trends (by category & mode)

High and low revenue-generating product segments

Operational differences between Express and Normal delivery

Fee distribution across categories and cities

🚀 How to Run the Project

Clone the repository

Install required Python libraries (pandas)

Run the Jupyter Notebook/Colab file

Load the dataset and execute the cells

📌 Future Enhancements

Build Power BI or Tableau dashboard

Implement predictive modeling for delivery delays

Add visualizations using Matplotlib/Seaborn
