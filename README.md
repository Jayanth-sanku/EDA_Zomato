## **ZOMATO DATASET OBSERVATIONS**

[View PDF Version Of My Analysis](https://github.com/Jayanth-sanku/EDA_Zomato/blob/main/ZomatoEDA.pdf)

## **1. Missing Values**
### - The only missing values in the dataset are found in the 'cuisines' column, with 9 missing entries.
### - Other columns like 'restaurant name', 'country', 'city', 'average cost for two', and 'rating' do not have missing data.

## **2. Country Distribution**
### - India has the highest number of restaurants listed in the dataset.
### - Other notable countries include the united states and the united kingdom, but india dominates the dataset.
### - The dataset seems to primarily represent the indian restaurant market, with significant presence in other countries.

## **3. Dataset Merging**
### - The zomato dataset was successfully merged with the 'country-code.xlsx' file to add the 'country' column.
### - This helps in associating each restaurant with its respective country, which will aid in country-based analysis.

## **4. Visualizations**
### - A pie chart was created to show the distribution of restaurants by country.
### - The chart clearly indicates that india has the highest proportion of restaurants in the dataset, validating zomato's presence in india.

## **5. General Dataset Structure**
### - The dataset contains useful columns such as:
### - 'restaurant name': name of the restaurant
### - 'country': the country where the restaurant is located
### - 'city': the city where the restaurant is located
### - 'cuisines': types of cuisines offered by the restaurant
### - 'average cost for two': the estimated cost for two people to dine at the restaurant
###  - 'rating': rating given to the restaurant by customers
### - These columns will be important for performing further analyses, such as restaurant ranking, cost analysis, and regional distribution of ratings.

## **6. Rating Analysis**
### - The 'rating' column is a key metric for understanding restaurant quality.
### - Further analysis of the 'rating' column across different cities and countries may reveal patterns in customer preferences.

