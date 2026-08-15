# Code Switching NLP — Urdu & English Language Identification

A Natural Language Processing project that identifies Urdu/Roman Urdu and English words in mixed-language text.

## Why This Matters

Roman Urdu and English are frequently used together in social media posts, chats, and informal communication. This code-switching project helps identify the language of individual words in mixed-language text, providing useful data for Urdu NLP and language identification applications.

## Project Goal

The goal of this project is to create and process a dataset containing naturally occurring Roman Urdu and English code-switching sentences for NLP research and language identification.

The dataset contains **150+ naturally occurring Roman Urdu and English code-switching sentences**.

## Labels

The dataset uses three labels:

* **URD** — Urdu / Roman Urdu
* **ENG** — English
* **MIX** — Mixed or ambiguous word

## How It Works

The project uses a labelled dataset containing Roman Urdu and English words and sentences. The text is processed and classified according to the language label assigned to each word. The resulting data can be used to train and evaluate NLP models for code-switching and language identification. The trained model is available through Hugging Face.

## Model

**Hugging Face Model:**
https://huggingface.co/Minahil-BSCS/urdu-eng-xlm-roberta

## 🌐 Live Demo

**Streamlit App:**
https://urdu-word-classifier-app-fo8aifmytruwmjmmf8ebgq.streamlit.app/

## 💻 GitHub Repository

**Source Code:**
https://github.com/MinahilFatima-BSCS/code-switching-codesaviours-si26-Minahil

## Demo Video

Watch the complete project demonstration:

**Loom Demo:** https://www.loom.com/share/5f2f21dd67d94009a784ee79a59166b4

## Dataset

* 150+ code-switching sentences
* Roman Urdu and English text
* Three labels: URD, ENG, MIX
* Dataset format: CSV

## Results

The final evaluation reported during the project includes:

* **URD F1 Score:** 0.95
* **ENG F1 Score:** 0.9665
* **Overall F1 Score:** 0.95826
* **Overall Accuracy:** 0.9599

## Technologies Used

* Python
* Google Colab
* Pandas
* Hugging Face Transformers
* XLM-RoBERTa
* Natural Language Processing
* Jupyter Notebook

## How to Run Locally

Clone the repository:

```bash
git clone https://github.com/MinahilFatima-BSCS/code-switching-codesaviours-si26-Minahil.git
cd code-switching-codesaviours-si26-Minahil
```

Install the required Python packages:

```bash
pip install pandas transformers torch datasets scikit-learn
```

Open the provided notebooks and run the cells step by step.

## Repository Contents

```text
code-switching-codesaviours-si26-Minahil/
│
├── SI26_Week6_Minahil.ipynb
├── SI26_Week7_Minahil.ipynb
├── dataset.csv
└── README.md
```

## Internship

This project was developed as part of the **Code Saviours SI-26 Machine Learning Internship**.

**Built by:** Minahil Fatima | Code Saviours SI-26 | 2026
