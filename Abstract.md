# Airlines-traffic-analysis
Geospatial Analysis of U.S. Airline Flight Routes and Fares (1993-2024)
Overview
This project focuses on the geospatial and statistical analysis of U.S. airline flight routes and fares from 1993 to 2024. The dataset, sourced from Kaggle, contains detailed information on airline routes, airport distances, passenger traffic, fare variations, and market shares of different airline carriers. The objective is to derive meaningful insights using data visualization, geospatial mapping, and statistical analysis techniques.

Technologies & Libraries Used
Python: The core programming language for analysis.
Pandas: For data manipulation, cleaning, and preprocessing.
Matplotlib & Seaborn: For statistical data visualization (histograms, line charts, scatter plots, box plots).
Folium: For interactive geospatial mapping of flight routes.
Google Colab: Used as the development environment to run the project seamlessly.

Methodology
Data Import & Cleaning
The dataset was uploaded in CSV format and read using Pandas.
Encoding issues and datatype inconsistencies were handled.
Missing values were dropped or corrected where necessary.
Geocoded city coordinates were extracted for mapping.

Geospatial Analysis
A Folium interactive map was created to visualize flight routes between origin and destination cities.
A Marker Cluster was implemented to improve visualization and reduce clutter.
Data formatting issues related to coordinate values were handled.
Statistical & Visual Analysis
Distribution of Average Fare: A histogram was generated to analyze fare variations.
Passenger Trends Over Time: A line plot visualized total airline passenger growth over the years.
Market Share of Largest Carriers: A box plot analyzed the dominance of top airlines.
Distance vs. Fare Relationship: A scatter plot examined how distance affects pricing.
Market Share of Lowest Fare Carriers: A box plot compared low-cost airline competition.

Results & Insights
Fare distribution revealed price fluctuations across different routes.
Passenger trends showed a gradual increase in air traffic over time.
Market dominance varied among major airlines, with some carriers consistently holding a higher share.
Distance and fare relationships indicated that longer distances do not always correlate with higher fares, possibly due to airline pricing strategies.
Budget airlines maintained competitive market shares, impacting fare structures across different routes.

Conclusion
This project successfully analyzed U.S. airline traffic trends and visualized flight routes using geospatial techniques. The insights derived can help stakeholders in the aviation industry, such as airlines, policymakers, and travelers, understand market dynamics and fare patterns. Future improvements could include predictive modeling for fare trends and incorporating real-time airline data for more dynamic insights.
