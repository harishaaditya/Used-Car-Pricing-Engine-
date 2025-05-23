# Used-Car-Prediction Model

Business problem statement (GOALS)
1.	Business Problem Understanding
CarDekho is an online platform in India for buying and selling new and used cars. Buying used cars is always a careful consideration for the customers. CarDekho seeks to optimize its used car business by accurately determining fair market value. By enhancing price prediction capabilities, the company aims to increase revenue, improve customer satisfaction, and gain a competitive edge in the Indian used car market.

2.	Business Objective
The business objective is to build a machine learning model that predicts the price of used cars which helps in assessing the true value of used cars to ensure fair pricing for both buyers and sellers.

3.	Approach
•	Data Understanding: Gather the data and understand the structure and content of the data and basic features.
•	Data Cleaning: Correcting data inconsistencies, handling missing values, removing duplicates.
•	Exploratory Data Analysis and Data Visualization: Summarizing data characteristics and visualizing the data to identify patterns, trends and relationships 
•	Inferential Statistics: Hypothesis testing and Feature Selection
•	Data Preprocessing: Handling outliers, Feature Engineering, Scaling, Transformation and Encoding.
•	Modeling: Building predictive models followed by evaluation and deployment
•	Reporting: Presenting the insights to the stakeholders with improved visualizations for effective communication.

4.	Conclusions
By developing a robust predictive model that accurately estimates used car values, this project aims to optimize pricing strategies, enhance inventory management, and ultimately drive revenue growth for Car Dekho. A deeper understanding of the factors influencing used car prices will empower the company to make data-driven decisions, improve customer satisfaction, and solidify its position as a market leader in the used car industry.
 
TOPIC SURVEY IN BRIEF
1.	Problem understanding
The biggest challenge while resale of used cars is to determine the fair market value of a used car due to factors like mileage, condition, model year, and regional variations. Establishing a resale price that meets the expectations of both buyers and sellers while ensuring the company's profit margins remains essential for business success.

2.	Current solution to the problem

Traditional used car pricing relies heavily on static factors such as vehicle make, model, and age. This manual valuation process often neglects dynamic market trends, regional price disparities, and the impact of vehicle condition and mileage on actual market value. As a result, the pricing strategy leads to suboptimal outcomes, including overpricing of older models and underpricing of in-demand vehicles, ultimately affecting overall profitability and revenue.

3.	Proposed solution to the problem

The proposed solution to the problem involves adopting a data-driven approach that gives a comprehensive understanding of the key factors that affect the resale of the used cars. This approach utilizes machine learning models to accurately estimate prices, ensuring more informed and precise pricing decisions. 

4.	Reference to the problem

The data has been obtained from Car Dekho and was downloaded from Kaggle. 
https://www.kaggle.com/datasets/sukritchatterjee/used-cars-dataset-cardekho?select=cars_data_clean.csv. The dataset is made publicly available for research and educational purposes


CRITICAL ASSESSMENT OF TOPIC SURVEY
•	Key area and Gaps identified:

The key area of focus is fair estimation of price of the used cars without compromising customer satisfaction, risk mitigation and increase in profit to the company. The project can add value by filling the gaps including overestimation of older models and underestimation of models that are in-demand. These gaps will lead to customer distrust and potential financial loss to the company.

•	Keys gaps being solved:

The key gap addressed is the improper pricing strategies. By analyzing the key factors affecting the value of used cars and building reliable prediction model, the project aims to provide optimal pricing of the used cars. 


METHODOLOGY TO BE FOLLOWED
Business Understanding: 

To build a machine learning model that predicts the price of used cars which helps in assessing the true value of used cars to ensure fair pricing for both buyers and sellers.
Data Understanding: 
•	The dataset contains 37813 rows and 66 columns.
•	The variables include 32 categorical, 31 numerical and 3 Boolean data types.

Data Preparation:
•	Data Preparation involves treating the data for anomalies and inconsistencies.
•	Handling missing values, duplicate records and appropriate treatment of outliers are crucial for model building.
•	Feature Engineering and Feature Selection will be performed to capture the relevant information and improve the model performance.
•	Transformation and Scaling will be performed on features, wherever necessary.
•	Encoding of categorical variables will be done for numerical representation which allows the algorithm to process the data and make the predictions.
 
Model Building:
•	To prevent underfitting or overfitting and for evaluating the model's performance, the dataset is split into training and testing sets.
•	The target feature (price) will be predicted using regression algorithms like Ordinary Least Squares (OLS), Classification and Regression Trees (CART), among others.
Model Evaluation:
•	Evaluating the performance of the models using the testing set is essential to ensure that they can make accurate predictions on new, unseen data.
•	The metrics used for model evaluation are R squared, Adjusted R Squared, MSE, MAPE and MAE. 
•	Hyperparameter tuning will be done to fine tune the hyperparameters for optimized values through methods like GridSearchCV and RandomizedSearchCV
•	Cross validation will be used to evaluate the model performance and avoid overfitting of the data.
Model Deployment:
•	Based on the evaluation metrics, the best performing model is chosen for deployment.
•	This model is integrated for making accurate price predictions for new and unseen data.
•	The model should be continuously monitored and updated with new data for optimization and improving the model efficiency.

 REFERENCES 
1. https://www.linkedin.com/pulse/used-car-market-india-challenges-opportunities-sheerdrive/
2. https://www.linkedin.com/pulse/driving-future-navigating-opportunities-challenges-indias-x9oaf/

Conclusions:

The final model has achieved a lower MAPE, indicating an improvement in accuracy.
The R² score has significantly improved, increasing from 65% to 98%.
However, the model shows signs of overfitting and may not generalize well to unseen data.
A major challenge with the dataset is the large number of columns, with about half requiring extensive data cleaning.
Proper feature selection and encoding techniques can help reduce overfitting and improve the model’s performance.

Limitations:

Impact of New Technologies: Rapid advancements like electric vehicles and autonomous driving can influence used car values, but data scarcity limits accurate predictions.
Ignoring Depreciation: Used car values depreciate nonlinearly based on factors like mileage and condition, which must be considered to avoid inaccurate predictions.
Interest Rate Influence: Changes in interest rates affect the affordability and demand for used cars, impacting their market prices.
Data Limitations: Regression models may lack generalizability and can produce biased results if the training data isn't representative of broader market conditions.

Learnings:
The dataset should be more relevant and not overly historical. 
Be prepared for extensive data cleaning !  
Perform feature selection when dealing with high-dimensionality. 
Implement better outlier handling methods. 
Always start early !


