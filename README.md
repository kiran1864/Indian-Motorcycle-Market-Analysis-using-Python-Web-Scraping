Project Overview:
This project focuses on collecting, cleaning, analyzing, and visualizing motorcycle data from BikeWale. The analysis was performed to understand motorcycle specifications, pricing, mileage, customer ratings, and brand-wise patterns.
The project uses Univariate, Bivariate, and Multivariate Analysis to identify useful relationships between different motorcycle attributes and provide meaningful insights for motorcycle comparison.

Objectives:
Collect motorcycle data from BikeWale.
Clean and prepare the collected dataset for analysis.
Analyze important motorcycle attributes such as CC, price, mileage, rating, power, and weight.
Compare motorcycles across different brands.
Identify relationships between different variables.
Visualize the findings using appropriate charts.
Generate useful insights and recommendations from the analysis.

Data Collection:
The motorcycle data was collected from BikeWale using web scraping.
The dataset contains information related to:
Brand
Motorcycle price
Engine capacity (CC)
Mileage
Customer rating
Power
Weight
The collected data was then stored and prepared for further analysis.

Data Cleaning:
Before performing analysis, the collected dataset was cleaned to improve data quality.
The major data-cleaning steps included:
Checking for missing values.
Handling incomplete records.
Converting values into suitable numerical formats.
Cleaning price values.
Cleaning engine capacity (CC).
Cleaning mileage, power, and weight values.
Preparing the dataset for visualization and statistical analysis.

After cleaning, the useful records were used for further analysis.

Exploratory Data Analysis
1. Univariate Analysis
Univariate analysis examines one variable at a time. It helps us understand the distribution and basic characteristics of individual motorcycle attributes.

Engine Capacity (CC)

A histogram was used to understand the distribution of engine capacities.

Result:
The chart shows the distribution of different engine capacities in the dataset and helps identify the commonly available CC ranges.

Price Distribution

A histogram was used to analyze motorcycle prices.

Result:
The chart shows how motorcycle prices are distributed across the collected dataset, from lower-priced to high-end motorcycles.

Customer Rating

A histogram was used to understand the distribution of customer ratings.

Result:
Most motorcycles have customer ratings concentrated around the higher rating range, showing generally positive ratings among the collected motorcycles.

Number of Bikes by Brand

A bar chart was used to compare the number of motorcycles available from each brand.

The dataset contains motorcycles from brands including:

Bajaj
Royal Enfield
TVS
Honda
Jawa
Triumph
KTM

Result:
Honda has the highest representation with 36 bikes, followed by Triumph and KTM with 31 bikes each. Jawa has the lowest representation with 5 bikes.

Mileage Distribution

A histogram was used to understand the distribution of motorcycle mileage.

Result:
The chart shows the range of mileage values and helps understand the fuel-efficiency pattern of the motorcycles.

2. Bivariate Analysis

Bivariate analysis studies two variables together to identify relationships and patterns.

CC vs Mileage

A scatter plot was used to analyze the relationship between engine capacity and mileage.

The average mileage by CC range was:

CC Range	Average Mileage
≤125 CC	56.56 kmpl
126–300 CC	39.71 kmpl
300–600 CC	30.74 kmpl
600–1200 CC	21.95 kmpl
1200–2458 CC	19.50 kmpl

Result:
The analysis shows that mileage generally decreases as engine capacity increases. Lower-CC motorcycles have better average mileage, while higher-CC motorcycles have lower average mileage.

Price vs Rating

A scatter plot was used to compare motorcycle price and customer rating.

Result:
Most motorcycles have ratings between approximately 4.0 and 5.0. The analysis also shows that a higher price does not necessarily mean a higher customer rating.

CC vs Price

A scatter plot was used to study the relationship between engine capacity and price.

Result:
Motorcycle price generally increases with engine capacity. Higher-CC motorcycles tend to belong to higher price ranges.

3. Multivariate Analysis

Multivariate analysis examines three or more variables together to understand more complex relationships.

CC, Power, Weight and Price

A bubble/scatter plot was used to compare:

Engine Capacity
Price
Power
Weight

Result:
The chart shows that motorcycle price generally increases with engine capacity. Higher-CC motorcycles also tend to have greater power and weight, while some high-end motorcycles have significantly higher prices.

Price, Rating and Mileage

A scatter plot was used to compare:

Price
Customer Rating
Mileage

Result:
Most motorcycles have ratings between 4.0 and 5.0. However, higher-priced motorcycles do not always have higher ratings or better mileage.

Brand, Price and Rating

A scatter plot was used to compare:

Brand
Price
Customer Rating

Result:
Different brands show different price and rating patterns. Most motorcycles have ratings around 4.0–5.0, while some expensive motorcycles have relatively lower ratings. This indicates that a higher price does not always result in a higher customer rating.

Key Insights
Motorcycle price generally increases with engine capacity.
Mileage generally decreases as CC increases.
Most motorcycles have customer ratings in the 4.0–5.0 range.
Higher-priced motorcycles do not always have higher ratings.
Higher-CC motorcycles generally have greater power and weight.
Different brands show different price and rating patterns.
Honda has the highest number of motorcycles in the analyzed dataset, while Jawa has the lowest representation.
Recommendations

Motorcycles should be compared using multiple factors such as price, mileage, rating, and engine capacity rather than considering price alone. Higher-CC motorcycles generally provide higher power and performance but tend to have higher prices and lower mileage. Customers can use these factors together to select motorcycles according to their requirements. Manufacturers can also use price, rating, mileage, and specification data to understand market patterns and customer preferences.

Challenges Faced
The major challenges faced during the project were:
Collecting motorcycle data through web scraping.
Handling missing and incomplete data.
Cleaning inconsistent values.
Converting price, CC, mileage, power, and weight into suitable formats.
Selecting suitable visualizations for different types of analysis.
Comparing multiple brands with different numbers of motorcycles.
Understanding relationships between multiple motorcycle attributes.
Conclusion
The project successfully collected, cleaned, and analyzed motorcycle data from BikeWale. Univariate analysis helped understand individual bike attributes, while bivariate analysis identified relationships between variables such as CC and mileage. Multivariate analysis provided a broader view by comparing price, rating, brand, CC, power, weight, and mileage together. Overall, the analysis provides useful insights for comparing motorcycles and understanding patterns in the motorcycle market.
