# Deep-Learning-Project
Deep learning-based sentiment analysis of mental health comments, classifying textual inputs as either positive or negative.

Overview

- **Task**: Binary sentiment classification (positive vs. negative)
- **Domain**: Ein Korpus für psychische Gesundheit
- **Approach**:  Sequential-Model in Keras (LSTM then Dense_Layer)
- **Goal**: Use natural language processing to support mental health research and improve digital empathy tools.

---

## 📁 Dataset

- **Source**: https://www.kaggle.com/datasets/reihanenamdari/mental-health-corpus
- **Size**: 27977 labeled comments
- **Classes**:
  1 means considered as a comment which is poisonous with mental health issues
  and 0 means not considered.
- **Preprocessing**:
  - Tokenization
  - Texts to Sequences
  - Padding and truncation for fixed input length
  - Data preparation
 
## 📁 Modelling
  - create and fit model
  - Model Evaluation
