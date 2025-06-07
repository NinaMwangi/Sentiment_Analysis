# Sentiment Analysis of Food Review
## Project overview
Within this project, we analyzed custom sentiment toward product on the Amazon particularly Food review. We have trained various model traditional, and Deep Learning model to find the one that performed better than the others. Within Traditional Model, we trained: ```Logistic Regression```, and ```Naïve Bayes```. And for the Deep Learning Model we trained: ```LSTM```, and ```GRU``` Models and we have evaluated their performance mainly focusing on the accuracy, F1-score, confusion matrix.

## Dataset
- **Source:** Dataset of [Food_Review](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) are from Kaggle platform.
- **Size:** Over 500,000 reviews
- **Columns:** review (Text) and sentiment (Label: Positive/Negative/Neutral)

## Model

## Performance of Model

| **Model**              | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
|--------------------|----------|-----------|--------|----------|
| **Deep Learning**                                                |
| ├─ GRU                 | 0.00    | 0.00      | 0.00   | 0.00     |
| └─ LSTM               | 0.00    | 0.00      | 0.00   | 0.00     |
| **Traditional Model**                                             |
| Logistic Regression| 0.8849   | 0.89      | 0.88   | 0.00     |
| Naïve Bayes        | 0.00   | 0.00      | 0.00   | 0.00     |


## Contributor
* **Nina Mwangi**: GRU_Model
* **Ruth Iradukunda**: LSTM_Model
* **Aubin Ntwali**: Naïve Bayes
* **Pascal Mugisha**: Logistic Regression


