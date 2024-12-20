### README: Negation Handling in Sentiment Analysis Project

This project evaluates and improves sentiment analysis using DistilBERT, focusing on negation handling. The four Jupyter notebooks included can be executed independently, provided the necessary datasets and Python packages are installed.

---

#### **1. Sentiment140Dataset.ipynb**
- **Purpose**: Fine-tunes DistilBERT on the Sentiment140 dataset for sentiment analysis, and provides tools to evaluate its performance in negation handling.
- **Dataset**: Sentiment140, a large-scale Twitter dataset (auto imported from Hugging Face)

---

#### **2. PangLLingDataset.ipynb**
- **Purpose**: Fine-tunes DistilBERT on the Pang and Lee dataset for sentiment analysis, and provides tools to evaluate its performance in negation handling.
- **Dataset**: Pang and Lee dataset pos and neg files (download sentence_polarity_dataset_v1.0 from [here](https://www.cs.cornell.edu/people/pabo/movie-review-data/)).

---

#### **3. PiyaDataset.ipynb**
- **Purpose**: Fine-tunes DistilBERT on the Piyasamara dataset for sentiment analysis, and provides tools to evaluate its performance in negation handling.
- **Dataset**: Piyasamara dataset (download [here](https://www.kaggle.com/datasets/dineshpiyasamara/sentiment-analysis-dataset)).

---

#### **4. NegationScopeMarking.ipynb**
- **Purpose**: Introduces and evaluates a negation scope marking mechanism to try improving DistilBERT's understanding of negation.
- **Dataset**: Piyasamara dataset (download [here](https://www.kaggle.com/datasets/dineshpiyasamara/sentiment-analysis-dataset)).
- **Key Features**:
  - Tags words downstream of a negation keyword with a special token
  - Special token added to DistilBERT vocabulary

---

### **Instructions**
1. Each notebook operates independently.

2. Download and open notebooks in Jupyter or JupyterLab

3. Run all cells from top to bottom to reproduce results. Install any required packages that are currently uninstalled.

4. Outputs include model accuracy, error analyses, and saliency plots for misclassified examples.

---
