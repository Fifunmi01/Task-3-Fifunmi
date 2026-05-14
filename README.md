# Task 3: AI Career Matchmaker (Recommendation Logic) 🎯

## Description
This repository contains my submission for Task 3 of the DecodeLabs Artficial Intelligence Internship.

This project marks the shift from basic classification to **Recommendation Systems** using Natural Language Processing (NLP) and vector mathematics. I built a practical "Tech Career Matchmaker" that analyzes a user's raw text inputs and mathematically aligns them with the optimal tech career path.

**Key Features & Architecture:**
* **Feature Extraction (TF-IDF):** Implements `TfidfVectorizer` to translate natural language user intent into mathematical arrays, automatically weighting domain-specific keywords.
* **The Math Engine (Cosine Similarity):** Utilizes `cosine_similarity` to calculate the precise geometric angle between the user's profile vector and the career attribute vectors.
* **AI Prediction Logic:** Built a dynamic sorting engine to rank the highest similarity scores and generate visual confidence bars to display match percentages.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas
* **Environment:** Google Colab / Jupyter Notebook

## How to Run
1. Clone this repository or download the code file.
2. Open `Task-3-Fifunmi.ipynb` in [Google Colab](https://colab.research.google.com/) or your preferred Jupyter environment.
3. Run the cells to initialize the knowledge base and test the Matchmaker Engine with custom user inputs.
