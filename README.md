# Intermediate Exam - Classifying Categories on the News Category Dataset

Student: Ana Carolina Souza

Dataset 1 source: https://www.kaggle.com/datasets/rmisra/news-category-dataset <br>
Dataset 2 source: https://www.kaggle.com/datasets/setseries/news-category-dataset/data <br>
Business case: https://arxiv.org/pdf/1810.00968

## Introduction
This project aims to classify news articles into categories. Two datasets from Kaggle are used for this purpose. The first contains around 210k news articles from the HuffPost containing 42 categories. The second dataset is a balanced version of the first one containing only 46k news articles with 10 categories from the original. The goal is to compare the performance of the models using both datasets.

The business case for this project is to help news agencies to classify their articles automatically, especially for historical data which is mostly unclassified. The research paper linked above details the importance of this task as well as best practices of the implementation of machine learning models in journalism.

## How to run

To run the project, you need to have Python installed on your machine. The project was developed using Python 3.8.5. You can install the required packages by running the following command:

```bash
pip install -r requirements.txt
```

The project is divided into two notebooks, one for each dataset. The first notebook is `main.ipynb` and the second is `main_balanced.ipynb`. The first notebook contains the analysis of the unbalanced dataset and the second contains the analysis of the balanced dataset. Both notebooks contain the same steps. The datasets are included in the repository inside the `dataset` folder.

Since retraining the model can be time-consuming, the models are saved in the `models` folder. The models are loaded in the notebooks to avoid retraining. In case you want to retrain the models, you can run the cells that train the models by deleting the models from the `models` folder.

## Report

A full report of the project can be found in the root of the repository in the file `report.pdf`. The report contains the business case, the methodology, the results, and the conclusion of the project, as well as the references used.