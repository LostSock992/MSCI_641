# Movie Genre Classification Using Machine Learning and Deep Learning Models

## Abstract:

Custom Multiple Genre Classification
The task of movie genre classification involves
categorizing movie plots into predefined genres based on their textual descriptions. This
project compares the performance of baseline
models including Naive Bayes, Logistic Regression, and Support Vector Machines (SVM)
against the advanced BERT model. While the
baseline models provide a solid starting point
for genre classification, the BERT model and
the DistilBert models, fine-tuned for this specific task, demonstrates superior performance.
Using the ”Wiki Movie Plots” dataset, we
evaluate the models based on accuracy, precision, recall, and F1-score. This comparative analysis enhances our understanding of
the strengths and limitations of traditional and
deep learning approaches in the context of
movie genre classification.

## Dataset:
I will use publicly available datasets containing movie plots and their associated genres.
The dataset used in this project was obtained from Kaggle. It contains 34,886 movie
descriptions scraped from Wikipedia. 
Link: https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots

## Supplementary Information:

### Notebook 1 Description (Bert_and_distilbert_models.ipynb):

The project involves a comprehensive analysis and comparison of various machine learning models, particularly focusing on transformer-based models like BERT and DistilBERT, for the task of movie genre classification using the "Wiki Movie Plots" dataset. The code begins by preparing the data, followed by fine-tuning the BERT and DistilBERT models over multiple epochs, with respective configurations of 3 epochs for BERT (taking 20 minutes per epoch) and 3 epochs for DistilBERT (taking 10 minutes per epoch). Model performances are evaluated based on metrics such as accuracy, precision, recall, and F1-score. Visualization of the results is accomplished through various plots including grouped bar charts for precision, recall, and F1 scores, and a radar chart to compare model performance across multiple metrics. Additionally, the project integrates MLOps practices for model deployment and monitoring, emphasizing scalability and user feedback mechanisms to iteratively improve model predictions. The project documentation includes the addition of a footnote hyperlink directing to the project's GitHub repository for easy access to the source code and further collaboration.


### Notebook 2 Description (Genre_Classification_Baseline.ipynb):

The project involves building and evaluating baseline machine learning models for the task of movie genre classification using the "Wiki Movie Plots" dataset. The project starts with Exploratory Data Analysis (EDA) to understand the dataset's structure, distribution of genres, and key statistics. EDA includes visualizations such as bar plots for genre frequency, word clouds for common terms, and histograms for text length distribution, providing valuable insights into the data. Following the EDA, the dataset is preprocessed, including steps like tokenization and TF-IDF vectorization to transform the text data into numerical features suitable for model training. Baseline models including Naive Bayes, Logistic Regression, and Support Vector Machines (SVM) are then trained on the dataset, and their performance is evaluated using key metrics such as accuracy, precision, recall, and F1-score. The code also includes visualizations to compare these performance metrics across the different models, providing a clear comparison of their strengths and weaknesses.



