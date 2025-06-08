# Sentiment Analysis of Food Review
## Project overview
Within this project, we analyzed custom sentiment toward product on the Amazon particularly Food review. We have trained various model traditional, and Deep Learning model to find the one that performed better than the others. Within Traditional Model, we trained: ```Logistic Regression```, and ```Naïve Bayes```. And for the Deep Learning Model we trained: ```LSTM```, and ```GRU``` Models and we have evaluated their performance mainly focusing on the accuracy, F1-score, confusion matrix.

## Dataset
- **Source:** Dataset of [Food_Review](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) are from Kaggle platform.
- **Size:** Over 500,000 reviews
- **Columns:** review (Text) and sentiment (Label: Positive/Negative/Neutral)

**Report:**: https://docs.google.com/document/d/1DBWFAR4ilHCKozB4nT18kl421dcMQj4eLa9SX_KrzTI/edit?usp=sharing

## Model

### Performance of Model

| **Model**              | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
|--------------------|----------|-----------|--------|----------|
| **Deep Learning**                                                |
| GRU                | 0.8292    | 0.76      | 0.83   | 0.79     |
| LSTM               | 0.8282  | 0.78      | 0.83   | 0.79     |
| **Traditional Model**                                             |
| Logistic Regression| 0.8572   | 0.84      | 0.86   | 0.84     |
| Naïve Bayes        | 0.8082   | 0.79      | 0.81   | 0.76     |
| SVM        | 0.8165   | 0.82      | 0.82   | 0.82     |


## How to Use
### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/NinaMwangi/Sentiment_Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Colab notebook:

### Running the Models
- Execute the notebook cells step by step.
- Modify hyperparameters as needed.
- Evaluate results using accuracy, precision, recall, and F1-score.

## Contributor
* **Nina Mwangi**
* **Aubin Ntwali**
* **Pascal Mugisha**
* **Ruth Iradukunda**

