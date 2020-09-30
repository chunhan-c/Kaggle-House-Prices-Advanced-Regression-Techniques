# Kaggle-House-Prices-Advanced-Regression-Techniques

此項目之目標為根據房屋各種特徵預測售出價格。  
數據來源 Kaggle: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview/description  
Training dataset中有1460欄，81個特徵(包括目標特徵"SalePrice")，Test dataset則是1459欄，80個特徵。

在這個Github展示了:
1. EDA應用。
2. 根據可能原因填補缺失值。
3. Feature engineering:target guided ordinal encoding, one hot encoding with many cates (KDD Orange比賽中獲勝之方法)。
4. Hyperparameter optimization。
5. Linear, Ridge, Lasso Regression, ElasticNet, Decision Tree, Random Forest, Adaboost, Gradient Boosting, XGBoost之應用。
6. Kaggle得分，如下圖:

![image](https://github.com/chunhan-c/Kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/Model_Performance.png)

在上述九個模型中，XGBoost表現得最好，Kaggle得分為0.13048，排名為1763/ 4818，前37%。
![image](https://github.com/chunhan-c/Kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/Best_score.png)
