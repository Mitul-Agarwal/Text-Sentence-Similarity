# Sentence Similarity Model Evaluation with TOPSIS

## 📌 Overview

This project evaluates multiple **Sentence Transformers** based on various performance metrics and ranks them using the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** decision-making approach.

## 🚀 Features

- Compares multiple **NLP models** for sentence similarity.
- Uses **cosine similarity, Euclidean distance, inference time, and model size** as evaluation metrics.
- Implements **TOPSIS** to rank the models based on weighted criteria.
- Provides **visualizations** using Matplotlib and Seaborn.

## 📊 Models Evaluated

- **sentence-transformers/all-MiniLM-L6-v2**
- **sentence-transformers/all-mpnet-base-v2**
- **sentence-transformers/distilbert-base-nli-stsb-mean-tokens**
- **sentence-transformers/bert-base-nli-mean-tokens**
- **sentence-transformers/roberta-base-nli-stsb-mean-tokens**

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/sentence-similarity-topsis.git
cd sentence-similarity-topsis

# Install dependencies
pip install numpy pandas sentence-transformers matplotlib seaborn
```

## 🛠 Usage

```python
python main.py
```

This script evaluates the models, applies TOPSIS, and generates a **bar plot** ranking the models.

## 📈 Results

- **Higher cosine similarity** is better ✅
- **Lower Euclidean distance, inference time, and model size** are better ✅
- TOPSIS provides an **overall ranking** based on these criteria.

## 🤖 Contributing

Feel free to **fork** this repository, create a new **branch**, and submit a **pull request**! 🚀


## 📞 Contact

For any queries, reach out via [LinkedIn](https://www.linkedin.com/in/yourprofile) or open an issue!

---

🌟 **If you like this project, don't forget to star the repo!** 🌟

