# XGBOOST-Predictive-Model-for-Car-Insurance-Claim
Introduction
According to the Insurance Information Institute report [4], the claims frequency, amount of claims per car, and claim severity are on the rise, e.g., accident claim severity increased by 35% for US car insurance between 2010 and 2019. The average US car insurance expenditure increased from USD $78,665 in 2009 to USD $100,458 in 2017 [4]. Prediction accuracy enables the insurance industry to adjust its premiums better and makes car insurance coverage more affordable for more drivers. Currently, many insurance companies are using ML methods instead of a conventional approach, which offers a more comprehensive way of producing a more reliable and representative outcome. A new study related to artificial intelligence and business profit margins was conducted by McKinsey & Company [5,6]. They showed that the businesses that have completely embraced artificial intelligence projects have generated a higher profit margin of 3% to 15%. However, selecting a suitable ML predictive model has yet to be fully addressed. 

In this project, we are considering a car insurance dataset from Kaggle. We start with EDA and identify variables with missing values and perform some missing data imputation methods. After that we will go through the process of feature selection. Eventually, we perform Extreme Gradient Boosting to identify the best possible predictive model.

Data Characterization
We have collected the data from Kaggle. The dataset has 10000 observations and 19 variables which are:
'ID', 'AGE', 'GENDER', 'RACE', 'DRIVING_EXPERIENCE', 'EDUCATION', 'INCOME', 'CREDIT_SCORE', 'VEHICLE_OWNERSHIP', 'VEHICLE_YEAR','MARRIED', 'CHILDREN', 'POSTAL_CODE', 'ANNUAL_MILEAGE', 'VEHICLE_TYPE','SPEEDING_VIOLATIONS', 'DUIS', 'PAST_ACCIDENTS', 'OUTCOME' among them 14 are categorical and 5 numerical. ‘OUTCOME’ is the response that a customer has claimed the insurance or not. 

Reference: 
[1] Mohamed Hanafy & Ruixing Ming (2022) Classification of the Insureds Using Integrated Machine Learning Algorithms: A Comparative Study, Applied Artificial Intelligence, 36:1, 2020489, DOI: 10.1080/08839514.2021.2020489
[2] Rawat, S., A. Rawat, D. Kumar, and A. Sai Sabitha. 2021. Application of machine learning and data visualization techniques for decision support in the insurance sector. International Journal of Information Management Data Insights 1 (2):100012. doi: 10.1016/j.jjimei.2021.100012.
[3] Baran, Sebastian, and Przemysław Rola. "Prediction of motor insurance claims occurrence as an imbalanced machine learning problem." arXiv preprint arXiv:2204.06109 (2022).
[4] https://www.iii.org/fact-statistic/facts-statistics-auto-insurance (accessed on 19 December 2020).
[5] Columbus, Louis. 2017. McKinsey’s State of Machine Learning and AI, 2017. Forbes. Available online: https://www.forbes.com/sites/louiscolumbus/2017/07/09/mckinseys-state-of-machine-learning-and-ai-2017 (accessed on 17 December 2020).
[6] Columbus, Louis. 2018. Roundup of Machine Learning Forecasts and Market Estimates, 2018. Forbes Contrib. 
Available online: https: //www.forbes.com/sites/louiscolumbus/2018/02/18/roundup-of-machine-learning-forecasts-and-marketestimates-2018 (accessed on 17 December 2020).
