Lyrics-Based Emotion Detection in Music Using Text Mining Techniques

This project classifies songs based on lyrical content for the growing demand of better user experiences and personal music recommendations. The main idea is to come up with a classifier that could determine whether a song is happy, sad, calm, or energetic based on the lyrics. It uses in-depth text analysis over data retrieved from kaggle to see word distributions which differ across categories of emotions. Achieving meaningful text representation, feature selection uses the Bag of Words (BOW) model, along with Part-of-Speech (POS) tagging and stemming through WordNet. The classification model built with Random Forest and XGBoost uses hyperparameter tuning through grid search to improve model performance. The outcome of this research demonstrates the effective application of text mining techniques in Python to analyze, categorize, and predict the emotion of music, thus offering a more personalized music experience for users.

Requirements:

Operating System:Windows 10/11, macOS, or Linux
Development Environment:Jupyter Notebook (preferred) or alternatives like VS Code with Jupyter extensions
Python Version:Python 3.8 or higher


Python libraries:

Data Handling:
pandas: For data manipulation and analysis
numpy: For numerical computations

Text Processing:
nltk: For text tokenization, stemming, and stopword removal
spacy: For advanced natural language processing
re: For regex-based text cleaning

Feature Extraction:
scikit-learn: For TF-IDF, Bag of Words, and machine learning models

Machine Learning:
xgboost: For building the mood classification model
sklearn: For Random Forest, model evaluation, and hyperparameter tuning

Other:
scipy: For statistical analysis
joblib: For saving and loading models

