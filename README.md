# Task 2: Smart IT Service Desk Classifier

## Project Overview
This repository hosts a production-grade Natural Language Processing (NLP) pipeline built to automate ticket sorting within an enterprise IT Asset & Technical Service Desk environment. By translating raw incoming service logs into intent categories and assigning distinct severity levels, the system optimizes queue routing and prioritizes business-critical system drops.

## Key Features
* **Distinct Asset Theme**: Customized data structure specifically modeled around infrastructure incidents (e.g., Network & Access drops, Hardware Failures, Software Crashes).
* **NLP Pipeline & Feature Extraction**: Integrates TF-IDF (Term Frequency-Inverse Document Frequency) text vectorization to tokenize and evaluate technical logs.
* **Logistic Regression Architecture**: Trains a multi-class predictive model to analyze incoming descriptions and instantly map routing destinations.
* **Advanced Evaluation Analytics**: Evaluates operational precision using structural confusion matrices rendered through unique color tracking palettes (`Greens`).
* **Live Operational Verification**: Features an integrated end-to-end routing check simulating inference validation on complex real-time strings.

## Tech Stack
* **Language**: Python
* **Libraries**: Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib

## How to Run
1. Load the Jupyter Notebook environment into Google Colab.
2. Run all execution paths to display the customized horizontal category split plots, severity volume structures, and the classification routing report.
