# 🧑‍🤝‍🧑CUSTOMER SEGMENTATION USING K-MEANS CLUSTERING:

## OVERVIEW:
This project involves customer segmentation based on their spending behavior using K-means clustering. A dataset containing customer information such as, customerID, age, gender is used to group these mall customers into distinct groups. 
- By clustering customers based on income and spending score, businesses can target specific groups of peoplr with tailored marketing strategies and offers.


## Dataset
The dataset contains 200 rows and 5 columns:
- 🆔  customerID: unique identifier for each customer
- ♂️  gender: male, female
- 👨‍🦲  age
- 💸  annual income: in thousands of dollars
- 💰  spending score: A score assigned to customers based on their spending behavior from (1 to 100) with higher scores indicating more spending


## Steps
1. ### Data Preprocessing:
- Handle missing data values ( if any)
- Standardize or normalize the data for better clustering results

2. ### Exploratory Data Analysis (EDA):
- Visualization of customer distribution by gender, age, income and spending score.
- Identify trends, outliers and relationships between variables.

3. ### K-means Clustering:
- Applying the algorithm to segment customers into clusters.
- Determine the optimal number of clusters

4. ### Visualization:
- Visualize in 2D space using features like annual income and spending score.
- Use scatter plots to illustrate how customers are grouped into segments.

5. ### Insights:
- Analyze the characteristics of each customer segment.
- Provide recommendations for each segment effectively.

  ## REQUIREMENTS
  To run this project, the following Python libraries are needed:
  - numpy
  -  pandas
  -  matplotlib
  -  seaborn
  -  sklearn
