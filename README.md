# Simple LLM-Based Sentiment Analysis

## Overview
This project performs sentiment analysis on a public dataset using a combination of large language model (LLM) embeddings and classical machine learning techniques. The goal is to evaluate the effectiveness of LLM representations for text classification tasks.

## Dataset
The dataset consists of tweets with the following attributes:
- **text**: The full text of the tweet.
- **selected_text**: The key phrase expressing sentiment.
- **sentiment**: Labels (neutral, positive, negative).
- **Metadata**: Includes tweet time, user’s age group, country, etc.

### Example Records
| textID      | text                                       | sentiment | Age of User |
|------------|-------------------------------------------|-----------|-------------|
| cb774db0d1 | I‘d have responded, if I were going      | neutral   | 0-20        |
| 549e992a42 | Sooo SAD I will miss you here in San Diego!!! | negative | 21-30        |
| 088c60f138 | my boss is bullying me...                | negative  | 31-45       |

## Methodology
1. **Data Preprocessing**
   - Clean and normalize text data.
   - Extract relevant fields for analysis.

2. **Embedding with LLM**
   - Use a pre-trained LLM (e.g., BERT, GPT) to generate embeddings.
   - Represent text as fixed-dimensional vectors.

3. **Classification**
   - Train classical ML models (e.g., SVM, Random Forest) using the LLM-generated embeddings.
   - Compare performance against traditional feature-based methods.

4. **Evaluation**
   - Use metrics such as accuracy, F1-score, and confusion matrix.

## Results
- Improved sentiment classification accuracy by leveraging LLM embeddings.
- Insights into how LLM representations interact with classical ML models.
- Demonstration of a hybrid approach combining modern NLP techniques with traditional models.


## Contributors
- Elyes Bouaziz
- Malek Belkahla
- Mohamed Amine Arous (Me :) )

## License
This project is open-source and available under the MIT License.

