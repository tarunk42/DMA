# Multiclass Classification for Predicting Faulty Water Pumps in Tanzania

This project aims to develop a predictive model
for identifying the status of water pumps as functional, in need
of repair, or non-functional based on various features related to
the pumps’ characteristics and management. The study utilizes
a comprehensive dataset containing 40 training features and 1
training label, with 30 categorical and 10 numerical columns.
Exploratory data analysis and preprocessing techniques are
applied to gain insights into the data’s completeness, handle
missing values, and address feature imbalances and redundancies.
Additionally, the CatBoost and Logistic regression algorithm
compared. The research also investigates the relationship between
the functionality status of water pumps and the population of the
areas in which they are installed. Furthermore, it identifies key
factors influencing the functional state of the pumps, offering
valuable insights for improving the availability of potable water
to communities. The results of the study show that the logistic
regression model achieves a commendable accuracy of 74% on
the test set. However, CatBoost, with hyperparameter tuning,
outperforms logistic regression, achieving an accuracy of 81.15%
