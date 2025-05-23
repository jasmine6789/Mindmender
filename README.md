# 🧠 MindMender: Early Depression Detection from Reddit Posts

MindMender is a Natural Language Processing (NLP) project designed to identify early signs of depression from Reddit posts. By analyzing user-generated content, this tool supports scalable, non-invasive mental health monitoring and visualization.

---

## 📌 Key Features

* **Data Preprocessing & Cleaning**: Text normalization, tokenization, and filtering.
* **Exploratory Data Analysis (EDA)**: Insights into linguistic patterns and dataset distribution.
* **Depression Detection Model**: Logistic Regression with TF-IDF vectorization.
* **Multi-label Emotion Classifier**: Sentence-BERT-based detection of co-occurring emotions.
* **High-Risk Post Alerts**: Flags posts with potential indicators of severe distress.
* **Interactive Dashboard**: Created using Dash directly within a Jupyter Notebook.

---

## 🔗 Skills & Concepts

* Natural Language Processing (NLP)
* Sentiment & Emotion Analysis
* Logistic Regression, TF-IDF Vectorization
* Multi-label Text Classification
* Interactive Visualizations with Dash

---

## 🛠️ Tools & Frameworks Used

* **Programming Language**: Python 3.x
* **Notebook Environment**: Jupyter Notebook
* **NLP Libraries**: NLTK, Sentence-BERT (via `sentence-transformers`)
* **Modeling & Evaluation**: `scikit-learn`
* **Visualization**: Plotly, Dash
* **Data Handling**: `pandas`, `NumPy`
* **Miscellaneous**: `matplotlib`, `seaborn`, `WordCloud`

---

## 📁 Repository Structure

| File / Folder             | Description                                                                     |
| :------------------------ | :------------------------------------------------------------------------------ |
| `UAI_final.ipynb`         | Complete codebase with preprocessing, modeling, and Dash dashboard.             |
| `final_dataset.json`      | Cleaned dataset for multi-label emotion classification (included).              |
| *(no standalone app.py)* | The interactive dashboard is implemented directly in the notebook.              |

---

## 📂 Datasets Used

We used three datasets to build and test the system:

1.  **`depression_dataset_reddit_cleaned.csv`**
    Labeled Reddit posts for binary depression detection.
    🔗 [Kaggle Source](https://www.kaggle.com/datasets/infamouscoder/depression-reddit-cleaned)

2.  **`final_dataset.json`**
    Custom emotion-labeled dataset used for multi-label classification (included in repo).

3.  **`data_to_be_cleansed.csv`**
    Raw Reddit mental health data (reserved for future use).
    🔗 [Kaggle Source](https://www.kaggle.com/datasets/neelghoshal/reddit-mental-health-data)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone [https://github.com/yourusername/mindmender.git](https://github.com/yourusername/mindmender.git)
cd mindmender
