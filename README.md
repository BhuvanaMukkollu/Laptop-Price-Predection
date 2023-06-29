# Laptop-Price-Predection
This project focused on utilizing linear regression to predict laptop prices based on various features, enabling consumers to make informed purchasing decisions and providing valuable insights for the laptop market.

Abstract:

This project focuses on the development of a laptop price prediction model using linear regression. The dataset comprises various features, including brand, processor, RAM, storage, graphics card, and screen size. The project involves data processing, exploratory data analysis (EDA), feature encoding, model training using linear regression from sklearn, coefficient significance testing using t-tests, error analysis through residual plots and QQ plots, and model evaluation using Mean Absolute Percentage Error (MAPE). The objective is to provide consumers with an accurate tool for predicting laptop prices and making informed purchasing decisions.

Introduction:
The prediction of laptop prices is crucial for both consumers and sellers to make informed decisions in the market. This project aims to develop a reliable laptop price prediction model using linear regression. By analyzing various laptop features, we can determine their impact on pricing and provide insights for consumers to make informed purchasing decisions.

Methodology:

Exploratory Data Analysis (EDA): The dataset is analyzed to understand the distribution, relationships, and statistical properties of the features. EDA techniques are applied to gain insights into the data and identify any data anomalies or outliers.

Data Preprocessing: The dataset undergoes data processing steps, including handling missing values, removing duplicates, and standardizing the data. Categorical features are encoded using techniques such as one-hot encoding to prepare the data for the linear regression model.

Assumptions Check for Linear Regression: The assumptions of linear regression, including linearity, independence, homoscedasticity, and normality of errors, are checked. Diagnostic plots, such as residual plots and QQ plots, are analyzed to assess the model's adherence to these assumptions.

Model Building: The linear regression model is trained using the preprocessed dataset. The features are used as predictors, and the laptop prices serve as the target variable. The model is implemented using the linear regression algorithm from the scikit-learn library.

Coefficient Significance Testing: The significance of the coefficients is tested using t-tests. This analysis helps determine the impact of each feature on laptop prices and identifies the most significant predictors.

Error Analysis and Model Evaluation: Residual plots and QQ plots are generated to assess the model's performance in terms of homoscedasticity and normality of errors. Additionally, the Mean Absolute Percentage Error (MAPE) is calculated to evaluate the accuracy of the model in predicting laptop prices.

Conclusion:
The laptop price prediction model developed in this project utilizes linear regression and provides consumers with a reliable tool to predict laptop prices. By considering various laptop features, the model can assist consumers in making informed purchasing decisions. The methodology encompasses data preprocessing, EDA, feature encoding, assumptions check for linear regression, model building, coefficient significance testing, error analysis, and model evaluation using MAPE. The project contributes to transparency in laptop pricing and enhances the consumer's ability to make informed decisions in the market.
