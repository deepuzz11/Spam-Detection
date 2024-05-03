# Email-SMS-Spam-Detection

## Spam Detection Project

### Introduction:
The project aims to develop effective machine learning models for detecting spam messages across various communication channels such as emails, text messages, and social media posts. By accurately identifying spam, the project contributes to enhancing cybersecurity measures for individuals and organizations, reducing the risks associated with malicious activities.

### Objectives:
1. **Data Collection and Preprocessing:** Gather and preprocess a diverse dataset containing labeled examples of spam and non-spam messages.
2. **Model Development:** Implement and train machine learning models, such as K-Nearest Neighbors (KNN) and Naive Bayes (NB), for analyzing text data and making predictions.
3. **Performance Evaluation:** Assess model performance using metrics like accuracy, precision, recall, and F1-score.
4. **Performance Improvement:** Explore techniques like feature engineering, hyperparameter tuning, and model selection to enhance model performance.
5. **Documentation and Communication:** Document the entire process for transparency and reproducibility.

### Data Collection:
- Utilized a publicly available dataset and supplemented it with additional collected data to ensure diversity.
- The combined dataset comprises 5572 samples, balanced between spam and non-spam messages.
- Preprocessing steps included label encoding, tokenization, normalization, stop words removal, and handling missing values.

### Exploratory Data Analysis (EDA):
- Analyzed message lengths, class-wise statistics, and word frequencies.
- Visualized distributions using histograms, word clouds, and bar plots.
- Identified frequent words unique to spam messages and potential class imbalances.

### TF-IDF Vectorizer:
- Utilized TF-IDF Vectorizer to convert text documents into numerical feature vectors.
- Combined TF and IDF to generate TF-IDF scores for each term in each document.
- Customized parameters for optimal feature representation.

### Model Selection:
- Explored various models and selected KNN and Naive Bayes based on accuracy and precision.

### Model Improvement:
- Adjusted max_features parameter in TF-IDF to control feature dimensionality.
- Implemented ensemble methods like voting and stacking classifiers to enhance predictive performance.

### Pickling of Model:
- Utilized the pickle module to store trained models for future use.
- Ensured consistency by saving preprocessing steps along with the model.
