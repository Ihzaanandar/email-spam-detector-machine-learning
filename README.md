# 📧 Email Spam Classification using TF-IDF and Random Forest

This project implements a machine learning pipeline for classifying
email messages as **spam** or **ham** (not spam).\
The workflow includes text preprocessing, TF-IDF vectorization,
hyperparameter tuning using RandomizedSearchCV, and model evaluation.

This notebook is designed as a complete end-to-end NLP project suitable
for portfolio presentation.

## 🚀 Project Objective

The goal of this project is to build a reliable text classification
model capable of detecting spam emails using Natural Language Processing
(NLP) techniques.

Specifically, the project aims to:

-   Clean and preprocess raw email text
-   Transform text into numerical features using TF-IDF
-   Train a classification model using Random Forest
-   Evaluate performance using accuracy scores
-   Test the model using real examples (spam and ham messages)

## 📂 Project Structure

    ├── data/
    │   └── emails.csv
    ├── spam-classification-project.ipynb
    ├── custom_template.tplx   (optional – used for PDF export)
    ├── spam-classification-project.pdf
    └── README.md

## 🛠️ Technologies & Libraries Used

-   Python 3.x\
-   NumPy\
-   Pandas\
-   NLTK\
-   Scikit-learn\
-   RandomForestClassifier\
-   TfidfVectorizer\
-   RandomizedSearchCV\
-   jcopml (for hyperparameter tuning)

## 📘 Notebook Contents

### 1. Importing Libraries

Basic Python, NLP tools, and machine learning libraries.

### 2. Data Loading

The dataset (`emails.csv`) containing text and spam labels is loaded
into a pandas DataFrame.

### 3. Train--Test Split

Data is split into training and testing sets using stratified sampling.

### 4. Pipeline Construction

A full ML pipeline is built containing: - TF-IDF Vectorizer for text
transformation\
- Random Forest Classifier as the prediction model

### 5. Hyperparameter Tuning

`RandomizedSearchCV` is used to search for optimal Random Forest
parameters.

### 6. Model Evaluation

Performance metrics: - Training accuracy\
- Cross-validation score\
- Test accuracy

### 7. Sanity Check

The model is tested using: - A spam-like promotional email\
- A ham (legitimate) message

## 📊 Model Performance Summary

The final model demonstrates strong classification ability with:

-   High training accuracy\
-   Strong cross-validation score\
-   Good generalization on test data

## ▶️ How to Run the Project

### 1. Clone the Repository

``` bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2. Install Dependencies

``` bash
pip install -r requirements.txt
```

### 3. Run the Notebook

``` bash
jupyter notebook
```

Then open:

    spam-classification-project.ipynb

## 📄 Exporting Notebook to PDF (Optional)

This project includes instructions to export the notebook to PDF with: -
Date\
- Title\
- File path

Run:

``` bash
jupyter nbconvert spam-classification-project.ipynb --to pdf --template custom.tplx
```

## 🧠 Key Learnings

-   Text preprocessing for NLP\
-   Converting text to numeric vectors with TF-IDF\
-   Building ML pipelines using scikit-learn\
-   Random Forest tuning with RandomizedSearchCV\
-   PDF generation using LaTeX templates\
-   End-to-end NLP model development workflow

## 📧 Contact

If you have any questions regarding this project or would like to
collaborate, feel free to get in touch.
