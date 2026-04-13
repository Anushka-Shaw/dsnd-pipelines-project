markdown# Pipeline Project

A machine learning pipeline that predicts whether a customer recommends a product based on their review. The pipeline handles numerical, categorical, and text data to train a Random Forest classifier.

## Getting Started

Instructions for how to get a copy of the project running on your local machine.

### Dependencies
python 3.11
scikit-learn
pandas
numpy
spacy
matplotlib
seaborn

### Installation

1. Clone the repository
git clone https://github.com/Anushka-Shaw/dsnd-pipelines-project.git

2. Install dependencies
pip install scikit-learn pandas numpy spacy matplotlib seaborn

3. Download the spaCy language model
python -m spacy download en_core_web_sm

4. Launch Jupyter Notebook
jupyter notebook starter.ipynb

## Project Instructions

Run all cells in `starter.ipynb` from top to bottom. The notebook will:
- Load and explore the data
- Build a pipeline for numerical, categorical, and text features
- Train a Random Forest classifier
- Fine-tune hyperparameters using RandomizedSearchCV
- Evaluate the model using accuracy, precision, and recall

## Files

- `starter.ipynb` - Main notebook containing all pipeline code
- `data/reviews.csv` - Dataset of customer reviews

## Built With

* **scikit-learn** - Machine learning pipeline and model
* **spaCy** - NLP lemmatization of text features
* **pandas** - Data loading and manipulation
* **matplotlib/seaborn** - Data visualization

## License

This project is licensed under the MIT License.