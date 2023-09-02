# Soccer Science: A Comprehensive Analysis of FIFA 19 Player Data

## Project Overview or Summary
Delving into the captivating realm of FIFA 19, this analysis offers a deep dive into player attributes, performance metrics, and the intricacies of gameplay. Spearheaded by Oyelade David Oluwapelumi, the study meticulously explores data, visualizations, and uses predictive modeling to understand player performance. The project's timestamp is 20th August 2020.

## Results or Findings (In-depth)
- Player Attributes: The dataset showcases diverse player attributes ranging from agility, balance, ball control, to more specific metrics like dribbling, shot power, and stamina. Histograms offer insights into the distribution of these attributes across players.
- Age and Potential: Scatter plots highlight the relationship between a player's age and potential, indicating that younger players generally have higher potential in the game.
- Top Clubs: The dataset brings to light top clubs like Real Madrid, Barcelona, and Juventus, emphasizing their prominence in the game.
- Position Analysis: Players occupy various positions on the field, from goalkeepers to forwards. The dataset offers a distribution of players across these positions.

## The Data Description
Sourced from Kaggle, the dataset offers a panoramic view of FIFA 19 player attributes. It encompasses details such as Player ID, Name, Age, Photo, Nationality, Flag, Overall rating, Club affiliation, and several performance metrics.

## Analysis of the Data 
The FIFA 19 dataset serves as a treasure trove of insights. Beginning with a methodical data cleaning process, anomalies and outliers were addressed. This meticulous preparation paved the way for an insightful exploratory data analysis. Delving deep into the data, trends emerged, revealing the age distribution of players, the prominence of clubs, and the diversity in player positions. Visualization tools brought these patterns to life, making them both comprehensible and engaging.

![Fifa Image](FIFA-IMAGES/download%20(8).png)
![Fifa Image](FIFA-IMAGES/download%20(9).png)
![Fifa Image](FIFA-IMAGES/download%20(10).png)
![Fifa Image](FIFA-IMAGES/download%20(11).png)
![Fifa Image](FIFA-IMAGES/download%20(12).png)
![Fifa Image](FIFA-IMAGES/download%20(13).png)
![Fifa Image](FIFA-IMAGES/download%20(14).png)
![Fifa Image](FIFA-IMAGES/download%20(16).png)
![Fifa Image](FIFA-IMAGES/download%20(15).png)

## Modeling: The Mathematical Logic Behind The Metrics
Modeling in this analysis primarily hinged on linear regression, aimed at predicting player performance.
- **Linear Regression:** A foundational predictive modeling technique, linear regression predicts a continuous target variable based on one or multiple independent variables. The underlying assumption is that there exists a linear relationship between the independent and dependent variables. In this context, the model was trained to predict player performance based on various attributes.
- **Model Performance:** The linear regression model showcased a Root Mean Square Error (RMSE) of approximately 2.78, indicating its predictive capabilities.

## Requirements
- **Libraries Used:** 
  - Data Manipulation: `pandas`
  - Visualization: `matplotlib`, `seaborn`
  - Predictive Modeling: `sklearn`
- **Software Version:** Python 3.x
- **Data Source:** The dataset can be accessed on [Kaggle](https://www.kaggle.com/).
