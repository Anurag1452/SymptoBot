# healthcare-chatbot
a chatbot based on sklearn where you can give a symptom and it will ask you questions and will tell you the details and give some advice.

# Prerequisites
Before running the HealthCare ChatBot, make sure you have the following prerequisites installed on your system:

Python (3.7+)
Required Python libraries (NumPy, pandas, pyttsx3, scikit-learn, etc.)
Data files (Training.csv, Testing.csv)
Symptom data files (symptom_Description.csv, symptom_severity.csv, symptom_precaution.csv)


# Data
The HealthCare ChatBot uses two main datasets: Training.csv and Testing.csv, which contain symptom data and corresponding prognoses.

Training.csv: This dataset is used to train machine learning models.
Testing.csv: This dataset is used to evaluate the performance of the models.
Additional symptom data is provided in the MasterData directory:

symptom_Description.csv: Contains descriptions of various symptoms.
symptom_severity.csv: Provides severity ratings for symptoms.
symptom_precaution.csv: Contains recommended precautions for symptoms.

# Features
The chatbot employs a Decision Tree Classifier and a Support Vector Machine (SVM) Using NLP for health condition prediction.
It utilizes symptom data and their associated descriptions, severity ratings, and precautions to assist users.
