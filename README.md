# Sentiment-Analysis-on-Amazon-Fine-Food-Reviews
Sentiment analysis on Amazon Fine Food Reviews using VADER and RoBERTa, with plans to fine-tune RoBERTa for improved results.

# 📦 Sentiment Analysis on Amazon Fine Food Reviews

This project performs sentiment analysis on the Amazon Fine Food Reviews dataset using both rule-based and transformer-based models. It currently compares **VADER** and **RoBERTa (pre-trained on Twitter data)** and plans to fine-tune RoBERTa in the next phase for domain-specific performance.

---

## 🔍 Objective

- Compare performance of **VADER** (lexicon-based) and **RoBERTa** (transformer-based).
- Explore how well a Twitter fine-tuned RoBERTa generalizes to food reviews.
- Visualize sentiment distribution across review star ratings (1 to 5).
- 📌 **Planned**: Fine-tune RoBERTa on this dataset to improve sentiment classification accuracy.

---

## 📁 Dataset

- Dataset: [Amazon Fine Food Reviews (Kaggle)](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- Fields used: `Id`, `Text`, and `Score`

---

## 🔧 Models Used

| Model        | Type         | Description                            |
|--------------|--------------|----------------------------------------|
| VADER        | Rule-based   | Lexicon-based sentiment analysis       |
| RoBERTa      | Transformer  | `cardiffnlp/twitter-roberta-base-sentiment` model (not yet fine-tuned on this data) |

---

## 📊 Sample Visualizations

- Pairplot of VADER and RoBERTa sentiment scores, colored by review ratings (1–5 stars)
- Examples of highly positive/negative reviews per model's perspective

