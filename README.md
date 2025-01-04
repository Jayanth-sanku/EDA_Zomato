# Observations from the Zomato Dataset Analysis

# 1. Missing Values
# - The only missing values in the dataset are found in the 'Cuisines' column, with 9 missing entries.
# - Other columns like 'Restaurant Name', 'Country', 'City', 'Average Cost for Two', and 'Rating' do not have missing data.

# 2. Country Distribution
# - India has the highest number of restaurants listed in the dataset.
# - Other notable countries include the United States and the United Kingdom, but India dominates the dataset.
# - The dataset seems to primarily represent the Indian restaurant market, with significant presence in other countries.

# 3. Dataset Merging
# - The Zomato dataset was successfully merged with the 'Country-Code.xlsx' file to add the 'Country' column.
# - This helps in associating each restaurant with its respective country, which will aid in country-based analysis.

# 4. Visualizations
# - A pie chart was created to show the distribution of restaurants by country.
# - The chart clearly indicates that India has the highest proportion of restaurants in the dataset, validating Zomato's presence in India.

# 5. General Dataset Structure
# - The dataset contains useful columns such as:
#     - 'Restaurant Name': Name of the restaurant
#     - 'Country': The country where the restaurant is located
#     - 'City': The city where the restaurant is located
#     - 'Cuisines': Types of cuisines offered by the restaurant
#     - 'Average Cost for Two': The estimated cost for two people to dine at the restaurant
#     - 'Rating': Rating given to the restaurant by customers
# - These columns will be important for performing further analyses, such as restaurant ranking, cost analysis, and regional distribution of ratings.

# 6. Rating Analysis
# - The 'Rating' column is a key metric for understanding restaurant quality.
# - Further analysis of the 'Rating' column across different cities and countries may reveal patterns in customer preferences.
