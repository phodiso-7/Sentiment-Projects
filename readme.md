# Sentiment Analysis of Client Feedback at a Drug Counselling Centre

## Project Overview

This project applies unsupervised sentiment analysis to feedback collected from clients at a drug counselling centre.
The clients were asked to give anonymous feedback within a character limit. The analysis focuses on three key experience categories:

- **Service received from counsellors**
- **Facilities at the centre**
- **Support programs offered**

Using pre-trained NLP models, the system automatically evaluates sentiment from client comments and assigns each a score on a **continuous scale from 1 to 10**, allowing for more nuanced understanding than binary classification.

---

##  Objectives

- Quantify client satisfaction in three distinct service areas.
- Identify clients with negative or neutral experiences.
- Extract common keywords from low-rated feedback to highlight specific issues.
- Recommend actionable improvements for each service category.

---

##  Tools & Technologies

- **Python**
- **Transformers (Hugging Face)** for sentiment analysis
- **KeyBERT** for keyword extraction
- **Matplotlib & Seaborn** for data visualization
- **Pandas** for data handling

---

##  How It Works

1. **Feedback Ingestion**: The system reads textual feedback from clients.
2. **Sentiment Scoring**: Each comment is analyzed using a pre-trained BERT-based model (`nlptown/bert-base-multilingual-uncased-sentiment`) and scaled to a 1–10 rating.
3. **Keyword Extraction**: For comments with low scores (< 2), KeyBERT extracts key issues for targeted insights.
4. **Actionable Output**: Insights help prioritize improvements to services, facilities, and programs.

---

## Sample Output

- Distribution plots of client satisfaction per category




## 🤝 Why It Matters

This project demonstrates how natural language processing can turn unstructured feedback into structured, actionable insights,helping support organizations improve care and engagement without manually labeling thousands of comments.




