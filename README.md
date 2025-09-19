# Project Title
Reviews Classification Project



## Getting Started
To run this project locally:

1. Clone the repository or download it as a ZIP file.
2. Ensure you have Python 3.11 installed (recommended).
3. Install the required libraries.



### Installation

```bash
# 1. Install packages
pip install pandas numpy scikit-learn spacy
# 2. Download spaCy language model
python -m spacy download en_core_web_sm
# 3. Run the script
python main.py



## Testing
# Run the entire script – it will print the evaluation scores.
# Note: this may take approximately 1.5 hours to complete, depending on the dataset size and your machine.



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

The project code is in the file Project_Model.



## Built With
Python 3.11 – programming language
pandas – loading and cleaning data
scikit-learn – pipeline, model, parameter search
spaCy – lemmatization and stopword removal
TfidfVectorizer – converting text to numerical features
Include all items used to build project.



## License
(LICENSE.txt)
