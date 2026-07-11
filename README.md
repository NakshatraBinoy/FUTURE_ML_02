# Task 2: Support Ticket Classification System

## Project Overview
This project focuses on building an automated Natural Language Processing (NLP) pipeline designed to ingest customer support text, accurately classify it into departmental categories, and dynamically assign priority tags (High, Medium, Low).

## Key Features
* **Text Preprocessing:** Leveraged TF-IDF Vectorization to filter out common stop words and mathematically weigh critical technical/billing terminology.
* **Multi-Target Analytics:** Trained separate Naive Bayes classification heads on the same text embeddings to simultaneously predict ticket domain and urgency levels.
* **Evaluation Metrics:** Evaluated performance utilizing classification reports detailing precision, recall, and F1-scores.

## Skills Gained
* Text preprocessing & tokenization.
* Natural Language Processing (NLP) classification
* Support analytics and multi-output routing logic
