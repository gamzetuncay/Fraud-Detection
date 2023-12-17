# Fraud-Detection
Imbalanced Classification of Fraudulent Credit Card Transactions Using Machine Learning
Credit card fraud is a significant and growing problem, with billions of transactions occurring every day around the world. Fraudsters are constantly adapting to new technologies, making it difficult to detect and prevent fraud. This study investigates the effectiveness of feature selection and sampling techniques with ML algorithms for imbalanced classification of fraudulent transactions. The model will be trained on a data set of over 284,000 credit card transactions, of which 0.172\% are fraudulent. A variety of ML techniques will be used, including Random Forests, Logistic Regression, XGBoost and CatBoost. In addition to ML techniques, resampling techniques to handle imbalance data and feature selection is used to improve the model's performance. The model's performance will be evaluated using a variety of metrics, including the confusion matrix, precision, recall, accuracy, F1-score, area under the curve (AUC) and Matthew’s correlation coefficient (MCC).

Note: Before going to the code it is requested to work on a jupyter notebook. If not installed on your machine you can use Google colab.


1. Download the dataset from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
2. Create a virtual environment and activate environment
```
$ virtualenv myenv
$ source myenv/bin/activate
```
3. File structure should look like this
   ```
    - Fraud-Detection
    -- creditcard.csv
    -- myenv
    -- project.ipynb
    -- requirements.txt
   ```
    
5. Run below code
```
pip install -r requirements.txt
```
5. Now you can open and run project.ipynb

