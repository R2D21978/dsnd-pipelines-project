

# Project Title

Reviews Classification Project  

## Getting Started

To run this project locally:  
1. Clone the repo or download as ZIP.  
2. Make sure you have Python (3.11 recommended).  
3. Install the required libraries.  
```

### Installation

```bash
# 1. Install packages
pip install pandas numpy scikit-learn spacy

# 2. Download spaCy language model
python -m spacy download en_core_web_sm

# 3. Run the script
python main.py


## Testing

Run the whole script – it will print Accuracy: at the end.
If accuracy looks good, then the model is working.

### Break Down Tests

Train-Test Split – checks how well the model performs on unseen data (20% of dataset).
RandomizedSearchCV – tries different RandomForest parameters and finds the best combination.

## Project Instructions


Load data from reviews.csv.
Split data into X (features) and Y (target label).
Preprocess features (numeric, categorical, and text).
Train a RandomForest model on training data.
Test the model on test data.
(Optional) Run parameter search to improve model performance.

## Built With

Python 3.11 – programming language
pandas – loading and cleaning data
scikit-learn – pipeline, model, parameter search
spaCy – lemmatization and stopword removal
TfidfVectorizer – converting text to numerical features
Include all items used to build project.

## License

(LICENSE.txt)
