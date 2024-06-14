# Telecom Churn Case Study(Part of kaggle competition)
> This case study focuses on developing machine learning models to predict churn among high-value customers in the telecommunications sector. The primary goal is to enable proactive measures such as personalized plans or discounts to retain customers. Additionally, the study aims to uncover key predictors of churn, enhancing understanding of customer decision-making processes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Main objective is to predict the churn rates of customers for a telecom service provider using the dataset provided.
- TThe dataset includes customer-level information with around 170 features, covering aspects like behavior, usage patterns, payment details, etc.
- Key steps include thorough data preparation, encompassing attribute identification, handling missing values, and standardizing data formats. Exploratory data analysis involves assessing variable relationships through correlation analysis, scatter plots, and advanced techniques like clustering. Feature engineering plays a pivotal role in creating new variables for improved model performance, while variable transformations ensure data readiness.
- Model selection involves evaluating various techniques such as logistic regression and tree-based methods, optimized through hyperparameter tuning and cross-validation. The chosen models are assessed using metrics like accuracy, precision, and recall. Insights from dimensionality reduction techniques like PCA inform feature importance analysis, facilitating strategic churn management recommendations to enhance customer retention strategies effectively.





## Conclusions
- EDA: Helped give an idea of which features could be potential key predictors of the churn rate.
- Models: The Random Forest model gave the best accuracy scores. However, the Logistic Regression model with hypertuning gave decent accuracy scores and had better sensitivity scores. 
- Identified the top 30 features that influenced the churn rate using a GridSearch pipeline with logistic regression as the estimator and 5 folds StratifiedKFold cross-validation. 


## Recommendations:
Based on the analysis of key predictors influencing churn probability in the telecom sector, here are targeted recommendations:

- `Promote Unlimited Local Calls`: Encourage packages with unlimited local calls to reduce churn, emphasizing ease of communication without additional charges.
- `Implement Circle-Specific Incentives`: Introduce schemes that incentivize local incoming calls within the same telecom circle, leveraging its significant impact on reducing churn.
- `Address ARPU Concerns`: Mitigate higher churn associated with Average Revenue Per User (ARPU) by:
- Clearly communicating the added value of higher ARPU through enhanced service benefits.
- Offering personalized discounts and loyalty programs to retain high-value customers.
- `Competitive Pricing for Outgoing and Roaming Calls`: Tailor competitive pricing packages for outgoing and roaming calls to counteract their contribution to churn.
- `Monitor and Adjust Competitive Strategie`s: Continuously monitor competitors' offerings and adjust pricing and service plans to remain competitive and retain customer loyalty.




## Technologies Used
- pandas - version 2.1.2
- numpy - version 1.26.1
- seaborn - version 0.13.0
- matplotlib - version 3.8.2
- sklearn - version 1.3.2


## Acknowledgements
- would like to thank UpGrad for giving us the oppurtunity to work on this project. 


## Contact
Created by [Imliyangla](https://github.com/Imliyangla) - feel free to contact me!


