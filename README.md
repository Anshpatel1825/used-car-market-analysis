# Analyzing the Used Car Market in India: Trends, Pricing, and Consumer Insights

# Project Overview
  - This project presents a detailed analysis of the used car market in India using real-world data. The main goal is to discover important trends, understand how      car prices are decided, and learn what customers prefer when buying second-hand cars. By using data science techniques such as data cleaning, Exploratory Data      Analysis (EDA), correlation analysis, and visualization, this project provides useful insights into how different features affect the selling price of used         cars.

  - The dataset includes over 7,000 used car listings with information such as car model, location, year of manufacture, kilometers driven, fuel type, transmission     type, number of previous owners, mileage, engine size, power, seating capacity, and price. These features are analyzed to find patterns in the market, compare      car types, and better understand customer behavior in the Indian used car industry.

# Dataset Information 
  - Total Entries: 7,253
  - Features: 14 Columns
- Column Name:
  - Location, Kilometers_Driven , Fuel_Type, Transmission, Owner_Type, Mileage, Engine, Power, Seats, Price

# Tools & Technologies Used
  - Python (Pandas, NumPy, Matplotlib, Seaborn)
  - Jupyter Notebook
  - Git & GitHub

# Key Features and Data Processing
  - Handled missing values and corrected inconsistent data types.
  - Extracted car brand information from the Name column and created a new Brand column.
  - Calculated car age based on the current year and the Year column, then created a new Car_Age column.
  - Dropped unnecessary columns such as Name, Year, Sr.No, and New_Price after feature extraction.
  - Performed descriptive statistics summarizing price distribution, mileage, engine size, and power.
  - Conducted correlation analysis to examine relationships between price and numerical variables such as kilometers driven, mileage, engine capacity, and power.
  - Trend analysis was done to understand how car prices vary by brand, fuel type, transmission, and owner type.
  - Created visualizations including histograms, box plots, count plots, pair plots, violin plots, and heatmaps to aid interpretation.

# Sample Visualizations
### Price Distribution
  - Histogram and box plot display the resale price distribution, highlighting common price ranges and spotting outliers.

### Category Counts
  - Count plots illustrate the frequency of different categories such as popular car brands, fuel types, and transmission types.

### Price vs Numerical Features
  - Pair plots compare Price with numeric features like Kilometers Driven, Engine Size, Power, Mileage, and Seats to find patterns.

### Price vs Categorical Features
- Violin plots show how Price varies with Fuel Type, Transmission, and Owner Type, providing insights into customer preferences.

### Correlation Heatmap
  - A heatmap displays correlations between numerical features including Price, Kilometers Driven, Engine, Power, Mileage, and Seats to identify strongest influencers on price.

# Key Insights
  - Market Size: Mumbai is the largest used car market in India, followed by Hyderabad and Pune. Ahmedabad has a smaller market share.
  - Fuel Type: Petrol and diesel cars dominate the used car market; CNG and LPG vehicles are minimal.
  - Transmission: Manual cars are nearly twice as common as automatics in the used car segment.
  - Ownership: Most used cars are owned by the first owner, indicating preference for fewer previous owners.
  - Seating: 5-seater cars are the most popular, likely because they suit small families and everyday use.
  - Brands: Maruti leads as the most common brand, followed by Hyundai and Honda.

 ### Price-related Insights from Numerical Features:
  - Weak negative correlation between Price and Kilometers Driven: Cars with higher kilometers tend to have slightly lower prices.
  - Very small positive correlation between Price and Mileage: Cars with better mileage may have slightly higher prices, but effect is minimal.
  - Moderate positive correlation between Engine Size and Price: Larger engines tend to command higher prices.
  - Strong positive correlation between Power and Price: Higher power output usually means higher resale price.
  - Strong negative impact of Car Age on price: Older cars generally sell for much less than newer ones.

# License
  - MIT License.
