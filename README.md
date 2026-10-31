# Python-Data-Analytics---Customer-Segmentation-Clustering
# Mall Customer Market Segmentation

This project uses unsupervised machine learning to group mall customers into approachable segments. By clustering individuals based on age, annual income, and spending scores, marketing teams can better understand and target specific demographic and behavioral profiles.

## Project Objectives
* Divide the mall's target market into approachable customer subsets.
* Identify the most important shopping groups for strategic planning.
* Determine the ideal number of segments and provide meaningful labels for each.

## The Approach
1. **Exploratory Data Analysis (EDA):** Analyze distributions and core relationships across customer attributes (`Age`, `Annual Income`, `Spending Score`).
2. **K-Means Clustering:** Implement the K-Means algorithm using the Elbow Method to identify the optimal number of distinct clusters ($K$).
3. **Summary Statistics:** Extract profile averages for each cluster to define and label the market groups.
4. **Visualization:** Build 2D and multivariate scatter plots to visually verify cluster separation and patterns.

## Dataset
The dataset (`Mall_Customers.csv`) contains basic information collected from cardholders, including:
* **CustomerID:** Unique ID assigned to each customer
* **Gender:** Male / Female
* **Age:** Customer age
* **Annual Income (k$):** Annual income in thousands of dollars
* **Spending Score (1-100):** Index assigned by the mall based on customer behavior and spending history


