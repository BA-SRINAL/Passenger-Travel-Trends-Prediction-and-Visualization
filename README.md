# Passenger-Travel-Trends-Prediction-and-Visualization

# Project Overview
In today’s highly competitive travel industry, understanding passenger trends is crucial for making informed business decisions. This project leverages Power BI, Power Query Editor, and DAX functions to predict and visualize passenger travel trends based on key features such as the country visited, the month of visit, and the total number of passengers. The insights derived from this project can help stakeholders optimize marketing strategies, forecast travel demands, and enhance overall operational efficiency.

# Problem Statement
The dataset includes detailed information about passenger visits to various countries. It contains fields such as the country visited, the month of the visit, and the total number of passengers. The challenge was to predict and visualize these travel trends effectively, allowing for better understanding and strategic planning within the travel industry.

# Objective

1. Predict passenger travel trends using historical data.
2. Visualize these trends in an intuitive and interactive manner.
3. Provide actionable insights to enhance decision-making processes.
   
# Tools & Technologies Used

1. Power BI: For data visualization and dashboard creation.
2. Power Query Editor: For data cleaning, transformation, and preparation.
3. DAX (Data Analysis Expressions): For advanced calculations and data modeling.
   
# Data Preparation & Modeling

1. Extracting Year from Month: Using DAX functions, I extracted the year from the "Month" column to create a new dimension that would facilitate time-based analysis.
2. Creating a Date Table: A "Date" table was generated using DAX, which included columns for Date, Year, Month Name, Month Number, Quarter, Weekday, and Week Number. This table served as a critical component for time-based data modeling.
3. Data Modeling: I performed data modeling to establish relationships between the main data table and the "Date" table. This step was essential for accurate time series analysis and trend prediction.
   
# DAX Calculations

To enhance the analytical capabilities of the dashboard, I created a series of DAX measures. These measures provided deeper insights into passenger travel trends, including:
1. Total Passengers: Aggregating the total number of passengers for various time periods.
2. Year-over-Year Growth: Calculating the percentage increase or decrease in passengers compared to the previous year.
3. Monthly Passenger Distribution: Analyzing passenger distribution across different months.
4. Top Visited Countries: Ranking countries based on the number of passengers.

# Data Visualization
Key features of the dashboard include:
1. Passenger Trend Analysis: Line charts and area charts to visualize passenger trends over time, with filters to view trends by country, month, and year.
2. Country-wise Analysis: A bar chart showing the top countries visited, along with their respective passenger counts.
3. Seasonal Trends: Visualization of passenger data across different quarters to identify peak travel seasons.
4. Interactive Filters: Slicers and dropdowns allowing users to explore the data based on various dimensions, such as country, month, and year.

# Insights & Impact

1. Travel Peaks and Troughs: Identified periods of high and low passenger traffic, allowing for better resource allocation.
2. Popular Destinations: Highlighted countries with consistently high passenger numbers, guiding marketing and promotional efforts.
3. Seasonal Patterns: Uncovered seasonal travel patterns, enabling more accurate demand forecasting.

# Conclusion

This project successfully transformed raw passenger visit data into a powerful tool for predicting and visualizing travel trends. The insights derived from the dashboard are instrumental in guiding strategic decisions within the travel industry.
