# About the Dataset
The "Don'tGetKicked" dataset served as the cornerstone of our study, providing rich insights into the domain of auto auctions. Comprising 72,983 rows and 34 columns in the training dataset, and 48,707 rows and 33 columns in the test dataset, this meticulously curated dataset offered a comprehensive representation of vehicles auctioned off.The dataset was obtained from kaggle

# Methodology
In this study, the methodology followed a systematic approach to leverage machine learning techniques for predicting problematic vehicles in auto auctions using the "Don'tGetKicked" dataset. The process commenced with a comprehensive exploration of the dataset, aiming to understand its structure and feature distributions. Subsequently, input and target columns were identified to define the classification task clearly. Missing numeric data were imputed using a simple imputer, while numeric features were scaled to ensure uniformity across different ranges. Categorical variables underwent one-hot encoding to prepare them for modeling. A baseline model was established by predicting the majority class to provide a reference point for subsequent models. Various machine learning algorithms including logistic regression, random forest, and gradient boosting were explored for classification. The selected models were then trained on the training dataset, with hyperparameters optimized as necessary. Evaluation of model performance was conducted using metrics such as accuracy, precision, recall, and F1-score on the validation dataset. Further refinement was achieved through fine-tuning the models by adjusting key parameters. The best-performing model was selected based on validation performance for subsequent analysis and deployment. Finally, potential avenues for future research and improvement were outlined, including the exploration of additional machine learning algorithms and comparative analyses.

# Introduction
In the context of the "Machine Learning with Python: Zero to GBMs" project, our aim was to delve into the application of machine learning techniques within the automotive industry, specifically focusing on predicting "kicked" cars in auto auctions. Leveraging a carefully curated dataset, our endeavor was to employ feature engineering techniques and fine-tune classifiers to deliver tangible value to dealerships. The primary objective of this study was to develop a robust model capable of accurately identifying cars likely to present issues, thereby assisting dealerships in making informed decisions during auctions. Through this project, we sought to showcase the potential of machine learning in enhancing decision-making processes within the automotive trading sector.

# Results
The experimentation with various machine learning algorithms yielded promising outcomes in predicting problematic vehicles in auto auctions. The logistic regression model achieved a validation accuracy of 89.74%, demonstrating its effectiveness in classifying auctioned cars. Furthermore, the random forest classifier exhibited notable performance, achieving a classification rate of 90.32% for the training data and 90.17% for the validation data after fine-tuning parameters such as max_depth and n_estimators. The XGBoost classifier, upon parameter optimization, demonstrated competitive accuracy with a training accuracy of 89.43% and a validation accuracy of 89.73%. Notably, significant features influencing model accuracy included wheel type, MMRAcquisitionAuctionCleanprice, MMRAcquisitionAuctionAverage price, and vehicle age. These results underscore the efficacy of machine learning algorithms in identifying kicked cars, offering valuable insights to dealerships for optimizing inventory selection and mitigating financial risks during auctions.

# Conclusion
In conclusion, this project undertook an exploratory analysis of the "Don'tGetKicked" dataset, employing various machine learning algorithms for classification. While all models demonstrated satisfactory accuracy, the random forest algorithm exhibited the highest performance. By accurately predicting problematic vehicles, these models offer invaluable assistance to dealerships in optimizing inventory selection and mitigating financial risks during auctions.

