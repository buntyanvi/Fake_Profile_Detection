# Social-Media-Fake-Account-Detection

![image](https://github.com/Vinod-Ghanchi/Social-Media-Fake-Account-Detection/assets/74112721/ccd3a946-ef1b-4ea1-bdae-eafcd7e91691)

#### Introduction
This project aims to address the issue of identifying fake social media accounts through the application of machine learning techniques. The dataset comprises profiles from both real and fake users, capturing relevant features such as status count, followers count, friends count, favorites count, listed count, language, and name. The preprocessing steps involve encoding categorical features, including language, and predicting the gender of users based on their names. These steps contribute to preparing the data for training and evaluation. The primary machine learning model utilized is XGBoost, a powerful gradient boosting algorithm. The dataset is split into training and testing sets, with the XGBoost classifier trained on the former. Cross-validation and learning curves are employed to assess the model's performance, providing an understanding of its generalization capabilities and learning behavior. While XGBoost is the primary focus, the project also hints at the potential exploration of other classifiers such as AdaBoost, Support Vector Machines (SVM), Random Forest, and Decision Trees. These alternatives could serve as benchmarks for comparing the effectiveness of the XGBoost model. The evaluation metrics include a confusion matrix, classification report, and classification accuracy. The confusion matrix allows for a detailed examination of true positive, true negative, false positive, and false negative predictions. The classification report provides additional insights into precision, recall, and F1-score for both fake and genuine classes. The classification accuracy represents the overall correctness of the model on the test dataset. By employing a diverse set of machine learning models and comprehensive evaluation metrics, this project aims to provide a robust framework for detecting fake social media accounts, contributing to the ongoing efforts in enhancing online security and trustworthiness.



## System Architecture Diagram:
![image](https://github.com/Vinod-Ghanchi/Social-Media-Fake-Account-Detection/assets/80514865/9d008a6c-ce37-40d5-b709-89661a60eafd)<br>



