# AI-Driven Urdu Poetry Generation Using Deep Learning, Large Language Models, and Retrieval-Augmented Generation

This repository contains the implementation notebooks developed for the M.Tech research project on AI-driven Urdu poetry generation. The project integrates dataset preparation, Small Language Model (SLM) fine-tuning, Retrieval-Augmented Generation (RAG), Large Language Model (LLM) inference, dataset analysis, and evaluation metrics.

---

# Google Colab Notebooks

## 1. Ghazal Dataset Preparation

**Colab Notebook:**
https://colab.research.google.com/drive/1M7t-Pk7pDg14KqLEJ8YG7W2xEYF2HYgn?usp=sharing

**Description**

* Collects and preprocesses the Urdu Ghazal dataset.
* Cleans and formats the dataset.
* Generates the final dataset used for model training.

---

## 2. Small Language Model (SLM)

**Colab Notebook:**
https://colab.research.google.com/drive/1_bAvljVqA3byxuMuh5r1Gcizeihw2b_J?usp=sharing

**Description**

* Fine-tunes the Small Language Model for Urdu poetry generation.
* Saves the trained model for inference.

---

## 3. Retrieval-Augmented Generation (RAG)

**Colab Notebook:**
https://colab.research.google.com/drive/1xmoIGSKliVMviU1gkSNgSQ5ctNFIeger?usp=sharing

**Description**

* Creates the FAISS vector database.
* Retrieves semantically relevant poetry.
* Generates context-aware Urdu poetry using Retrieval-Augmented Generation.

---

## 4. Dataset Statistics

**Colab Notebook:**
https://colab.research.google.com/drive/18cxcU91Jep9WNjK9tzTTvMWu-nwIN1BW?usp=sharing

**Description**

* Performs statistical analysis of the dataset.
* Generates dataset summaries and visualizations.

---

## 5. Large Language Model (LLM) Example

**Colab Notebook:**
https://colab.research.google.com/drive/1LFQxrUkRMvnjgYlqjlqsh2cAyIQHz6Gd?authuser=3

**Description**

* Demonstrates Urdu poetry generation using the Large Language Model.
* Includes inference examples.

---

## 6. Evaluation Metrics

**Colab Notebook:**
https://colab.research.google.com/drive/1fp-fYWDUPt10bTt8orGTO9fFv5_RyAiC?usp=sharing

**Description**

* Evaluates the generated poetry.
* Computes the performance metrics used in the project.

---

# How to Execute the Notebooks

1. Open the required Google Colab notebook using the corresponding link above.
2. Select **Runtime → Change runtime type → T4 GPU** (recommended for model training and inference).
3. Execute the notebook cells sequentially from top to bottom.
4. Mount Google Drive if prompted.
5. Update dataset, model, or file paths if required before execution.

---

# Note

* Some notebooks require GPU acceleration.
* Ensure all required datasets and model files are available before execution.
* If output cells are not visible, simply execute the notebook to reproduce the results.
* For detailed methodology, implementation, and experimental analysis, please refer to the accompanying project report.
