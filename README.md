Zomato Restaurant Analysis

📌 Project Overview
Zomato is a restaurant search and discovery service that operates in several countries worldwide. This project aims to analyze Zomato's restaurant data to identify trends and insights, helping stakeholders understand their business performance better.

🎯 Business Requirements
The primary objectives of this analysis are:
1. Identify the total number of restaurants across continents, countries, and cities.
2. Enable both global and granular-level analysis of restaurants.
3. Rank top-performing restaurants based on customer ratings.
4. Identify top restaurants based on affordability (least average cost).
5. Provide filtering capabilities based on:
   - Continent, country, and city
   - Services like online delivery or table booking
   - Average rating categories
6. Identify restaurants with the highest number of cuisines served.
7. Create a multi-page Power BI report with easy navigation.
8. Ensure the report is accessible via web browsers and mobile devices.

🛠 High-Level Steps
1. Data Import: Load restaurant data from multiple Excel files.
2. Data Transformation: Clean and preprocess the data (fix city names, remove unused columns, create new tables, etc.).
3. Data Modeling: Define relationships between tables, ensuring correct cardinality and filter directions.
4. Data Manipulation: Categorize geographic columns, create user-defined hierarchies, and group countries into continents.
5. Using DAX (Data Analysis Expressions):
   - Define a "Rating Color" column based on the rating scale.
   - Create measures like Restaurant Count, Average Cost, Average Rating, and Cuisine Count.
   - Map countries to continents.
6. Data Visualization: Develop interactive Power BI reports with:
   - Cards displaying key metrics (Average Cost, Average Rating, Restaurant Count)
   - Maps showing restaurant distribution
   - Slicers for filtering data
   - Infographic designer visuals for top restaurants
   - Gauges to visualize restaurant ratings and costs
   - Navigation buttons for an intuitive user experience
7. Publishing & Accessibility:
   - Publish the report on Power BI Service
   - Generate a public link for browser access
   - Optimize the report for mobile viewing

 🏗 Dataset Details
The dataset consists of multiple Excel files containing restaurant information across different continents. Key tables include:
- **Restaurant Data**: Restaurant name, address, city, country, cuisines, average cost, rating, etc.
- **Geographic Data**: Country codes and continent mappings.
- **Fact Table**: Aggregated restaurant-related metrics.

 🖥 Tools & Technologies Used
- **Power BI** (for data visualization and reporting)
- **Excel** (for data storage and preprocessing)
- **DAX** (for calculations and aggregations)



