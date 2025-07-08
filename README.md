SENTIMENT ANALYSIS WITH NLP<br/>
INTRODUCTION<br/>
------------<br/>

This project demonstrated sentiment analysis using TF-IDF vectorization and Logistic Regression. The preprocessing steps cleaned the text data, the TF-IDF vectorizer converted text to numerical features, and the Logistic Regression model classified sentiments. The model was evaluated using standard metrics, and we showed how to predict sentiments for new reviews.</br>


OUTPUT:<br/>

Classification Report:<br/>
      precision &nbsp;&nbsp;&nbsp;recall&nbsp;&nbsp;&nbsp;f1-score&nbsp;&nbsp;&nbsp;support<br/>
           0&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.001<br/>
           1&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.001<br/>
    accuracy&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;2<br/>
   macro avg&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;2<br/>
weighted avg&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;1.00&nbsp;&nbsp;&nbsp;2<br/>

Confusion Matrix:<br/>
[[1 0]<br/>
 [0 1]]<br/>

Review: This product is fantastic!<br/>
Predicted Sentiment: Positive<br/>

Review: Awful experience.<br/>
Predicted Sentiment: Negative<br/>
