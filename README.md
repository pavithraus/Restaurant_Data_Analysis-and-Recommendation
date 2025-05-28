# Restaurant_Data_Analysis-and-Recommendation

## Resources used

- **Dataset : Restaurant_dataset.csv
-
## Problem Statement

**Stage 1: Data exploration and analysis**

- **Objective:** Acquire basic skills in data exploration, descriptive analysis, and geographic insights for a restaurant dataset.
- **Tasks:** Explore data structure, address missing values, perform data conversions, and analyze class imbalances. Calculate statistical measures, examine distributions of categorical variables, and identify the best cuisines and cities.
- **Meaning:** Develop basic data science skills for the hospitality industry and data-driven decision making.

**Level 2: Advanced Analysis**

- **Objective:** Improve insights from the restaurant dataset through tasks focused on table reservations, delivery services, pricing and feature engineering.
- **Tasks:** Calculate the percentage of table reservations and online delivery, compare ratings for restaurants with and without reservations, and analyze the availability of online delivery. Determine the most common price range, calculate the average ratings for each price range, and assign colors to the highest rated categories. Utilize feature engineering techniques for improved data intelligence.
- **Meaning:** Deepen understanding and provide valuable insights into customer preferences, services, pricing and data enrichment.

**Level 3: Predictive Modeling and Insights**

- **Objective:** Perform predictive modeling, customer preference analysis and data visualization to gain deeper insights.
- **Tasks:** Build regression models to predict restaurant ratings, evaluate model performance, and compare algorithms. Analyze the relationship between cuisine types and ratings, identify popular cuisines, and identify specific cuisines with higher ratings. Create visualizations to show the distribution of ratings, compare average ratings, and visualize relationships between features.
- **Meaning:** Improve decision making, understand customer preferences and predict restaurant ratings by providing comprehensive insights into the restaurant data set.

---

## Project summary

**Stage 1: Data exploration and analysis**

- Performed extensive data analysis and pre-processing to ensure data integrity.
- Performed descriptive analysis, extracted key statistical measures and identified popular cuisines and cities.
- Explored geographic insights, visualized restaurant locations and investigated correlations with reviews.

**Level 2: Advanced Analysis**

- Analyzed table reservations and online delivery services to gain insights into customer preferences and availability.
- ![image](https://github.com/user-attachments/assets/08eed54e-8e07-4980-adfa-ac63f6308af9)

- Identified the most common price range and correlated it with the highest average rating.
- Advanced feature engineering to improve the intelligence of the dataset.

**Level 3: Predictive models and insights**

- Create regression models to predict the overall rating of restaurants, with Random Forest performing best.
- Investigate the relationship between cuisine types and restaurant ratings.
- Analyzed data visualizations to reveal the distribution of ratings and other insights.

**Total Insights**

The project included in-depth data analysis, predictive modeling, and customer preference insights. These insights provide valuable information for data-driven decision making, customer preferences and restaurant review prediction.

---

## Conclusion

**1. data overview and exploration:**

- The dataset comprises 9,551 restaurant records with 21 columns.
- Only a few null values were detected, especially in the 'Cuisines' column.
- There were no duplicates and no data type conversion was required.
- The distribution of the 'Overall rating' showed a balanced pattern.

**2. descriptive insights:**

- The key statistical metrics for the numeric columns were identified.
- The top country codes were 1 and 216, while cities like New Delhi, Gurgaon and Noida led in the number of restaurants.
- The most popular cuisines include North Indian and Chinese.
- ![image](https://github.com/user-attachments/assets/3c718452-d322-4561-bfe6-8ebfa8ef5d38)


**3. Geographical analysis:**

- North America and Asia, especially India, led in terms of restaurant presence.
- New Delhi emerged as the city with the most restaurants, followed by Gurgaon, Noida and Faridabad.
- Latitude showed no correlation with the ratings, while longitude showed a negative correlation.
- ![geoloc](https://github.com/user-attachments/assets/ab20c3bf-f03c-4aa6-a61a-0f6b54e82df3)



**4. analysis of table reservation and online delivery:**

- Approximately 12.12% of restaurants offered table reservations and 25.66% offered an online delivery service.
- Restaurants with table reservations had a significantly higher average rating of 3.44, compared to 2.56 for restaurants without this service.
- Online delivery service was more prevalent in restaurants with mid-priced food.

**5. analysis of the price range:**

- Price band 1 was the most common among restaurants.
- Restaurants in price range 4 scored the highest average rating, followed by price ranges 3, 2 and 1.

**6. feature engineering:**

- Two new columns, 'Length of Restaurant Name' and 'Length of Address', were created based on the length of restaurant names and addresses.
- Two binary columns, 'Has table reservation' and 'Has online delivery', were introduced by categorical variable coding.

**7. insights into predictive modeling:**

- Three regression models, linear regression, decision tree and random forest, were used to predict overall restaurant ratings.
- Random Forest outperformed the other models and had the lowest mean squared error (MSE) and the highest R-squared value.

**8. analysis of customer preferences:**

- Different cuisines such as Café, Mughlai, North Indian cuisine and fast food had a significant impact on the ratings of the restaurants, performing differently.
- North Indian and Chinese cuisines showed greater variability in ratings, while café and fast food cuisines showed more consistent ratings.
- In terms of number of votes, North Indian, Mughlai and Chinese cuisines were the most popular.
- Italian, Hawaiian, seafood, tea, sandwich, continental and Indian cuisines received the highest average ratings.

**9. data visualization highlights:**

- Restaurant ratings followed a negatively skewed distribution.
- Italian, Hawaiian, seafood, tea, sandwich, continental and Indian cuisines secured the top spots in terms of highest average ratings.
- Cities such as Inner City, Quezon City and Makati City were identified as the most popular based on the highest average rating.
- A positive correlation was found between the votes and the restaurant ratings.

This comprehensive project journey provided insights into restaurant data, customer preferences, pricing, services and predictive modeling, contributing to a holistic understanding of the restaurant industry.
---
