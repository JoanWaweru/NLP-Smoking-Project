# 🧠 Smoking-Related Medical Q&A Chatbot
This project is a medical question-answering chatbot focused on smoking-related health topics such as nicotine addiction, secondhand smoke, lung cancer, and respiratory effects. It leverages biomedical literature metadata from the CORD-19 dataset (Kaggle version) and uses vector embeddings, chunked document search, and a conversational LLM to deliver factual, context-aware responses.

## 📚 Dataset
- Source: CORD-19 Metadata Dataset on Kaggle

- Abstracts filtered using the keywords: 'smoking', 'smoke', 'tobacco', 'nicotine', 'cigarette', 'vaping', 'e-cigarette', 'secondhand', 'lung cancer'.

## 🧰 Technologies Used
- Python — for preprocessing, analysis, and automation

- LlamaIndex — to build and query a semantic vector index

- HuggingFace Transformers — for embedding (BioBERT) and language generation (LLaMA)

- Gradio — to create an interactive web-based chatbot UI

- Google Colab + Drive — for cloud execution and persistent storage

## 📌 Features
- Filters metadata abstracts from the CORD-19 Kaggle dataset for smoking-related topics

- Validates and visualizes keyword distributions and abstract lengths

- Chunks text into semantically searchable units

- Builds a persistent vector store index using BioBERT embeddings

- Answers user questions via a LLaMA-based medical chatbot

- Memory-aware Gradio chat interface with reset capability

## 🚀 How to Run
1. Open the notebook in Google Colab.

2. Run all cells to:

    - Load and preprocess data
    - Validation and Visualization
    - Create and persist the vector index
    - Launch the chatbot UI

## 🧠 Example Queries
1. "What are the effects of secondhand smoke?"

2. "Does smoking increase the risk of lung cancer?"

3. "What is the impact of nicotine on the lungs?"

4. "How does smoking relate to COVID-19 outcomes?"

## 🛡 Disclaimer
This chatbot is intended for educational and informational purposes only.
It does not constitute professional medical advice.
Please consult a healthcare provider for any medical concerns.

## 👤 Author
Developed by Joan Waweru
Built as part of a research project combining NLP, biomedical data, and public health education.
