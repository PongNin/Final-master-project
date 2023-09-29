# Coding and Raw dataset

## Dataset

### Brazilian E-Commerce Public Dataset by Olist : [link](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download)

### Abstract
In this project, we investigate the performance of machine learning (ML) to predict customers’ satisfaction score from the sales dataset collected by Olist, the Brazilian e-commerce company. Customer satisfaction score is categorized into 4 classes: Low, Average, Good and Excellent where majority of sales orders receive Excellent score. Inspired by the fact that delivery duration and product rating score obtained from other customers’ purchase are one of the main factors that influence customer’s satisfaction score, we propose a feature engineering method that creates delivery duration and the average product rating score which are used as the main features in the ML model. We employ Random Forest (RF), Logistic Regression (LR), and K-Nearest Neighbor (K-NN) to predict customers’ satisfaction score and their performance are compared with the baseline model which predicts the customer satisfaction score using the average product rating score. Results show that RF model yields the best performance with the average precision, recall, and macro F1 equal to 0.34, 0.36, and 0.32, respectively. In addition, RF achieves the best recall equal to 0.43, 0.33 and 0.33 for Low, Average and Good classes. The mean and SD of the product rating are two features with the highest feature importance equal to 0.313 and 0.087, respectively.
