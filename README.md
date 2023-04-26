**Objective:**

* To find the relation between the features (RAM, phone dimensions, camera quality, etc.) of the phone and the selling price.
* To identify the Classification model which accurately predicts the price range of the phones based on features

**Introduction**

Mobile phones are one of the most common and most in-demand electronic devices in today’s times. This device has revolutionized our society and simplified our lives in many ways. Mobile phones have enabled us to easily communicate with people all over the globe regardless of where we are, stay informed with the help of the internet, play music, videos, and games, take photos and videos, store and share considerable amounts of data, conduct monetary transactions and much more. The demand for mobile phones grows in tandem with technological advancements, every year. Needless to say, there are a large number of companies competing in this market right now. Therefore, companies want to understand the sales data of mobile phones and the factors that drive the prices.

**Conclusion**

**Findings from EDA:**

* Relatively expensive phones have more RAM and higher capacity batteries.
* Most of the phones do not contain front camera or have low quality front cameras.
* Expensive phones have better pixel resolution
* Premium price range phones are light-weight and have wider screens as compared to phones in the lower price ranges.

**Conclusion from Evaluation of Models:**

* The best features for predictive modeling was taken, by using K best feature selection method with the Chi-square statistic.
* Implemented various classification algorithms, out of which the SVM(Support vector machine) algorithm gave the best performance after hyper-parameter tuning with 98.3% train accuracy and 97 % test accuracy.
* XG boost is the second best good model which gave good performance after hyper-parameter tuning with 100% train accuracy and 92.25% test accuracy score.
* KNN gave a very worst model performance on this dataset.
* checked for the feature importance from each model. RAM, Battery Power, Px_height, and px_width contributed the most while predicting the price range.
