# Capstone_Project_AirBnb_Bookings_Analysis

- **Industry Context:**

Airbnb is a brand known globally in the property rental/hospitality industry, offering travelers flexibility, affordable, and localized alternatives compared to hotels. The platform caters to a growing preference for personalized and immersive travel experiences, especially for people who prefer independent stay, flexibility and budget constraints. In major cities like New York, where hotel prices are too high and demand is constant, Airbnb property listings have surged in both number and variety.

However, the property rental industry also faces increased scrutiny from city regulators, with concerns about housing affordability, zoning violations, and community impact.

- **Project Objective**

The primary business objective of this exploratory data analysis is to help Airbnb hosts, property managers, and investors optimize their listings to improve occupancy rates, revenue, and overall performance.

- **About Data**

The  dataset contains airbnb listing data for the year 2019 and has around 49,000 observations in it with 16 columns and it is a mix of categorical and numeric values.

There are no duplicate values in the dataset.

- **Data Preprocessing**

The columns Name and Host name had missing values, they are filled with 'N/A' since their count is very low and it won't make much difference in our further analysis. The review_per_month column was filled with 0 where the values were missing, which typically means that the property has not received any reviews, so assuming the same for our case and replacing null values with 0 makes sense.

- **Actionable Insights**
    - Manhattan being the most expensive neighbourhood with the highest average price we can infer that it could be driven by higher demand
    - Staten Island and the Bronx show lower overall review counts across all room types, which may indicate less activity or fewer listings in these neighborhoods.
    - The majority of listings are for "Entire home/apartment" constituting 52.0% of the total listing.
    - Shared room has the lowest average price, making it the most affordable across all the neighborhood and preferred listing for people on a low budget.
  
- **Key Results**

Uncovered pricing distribution, property listing availability and popularity and understood the demand and preferences of customers on the basis of geographical location, room type, pricing.
