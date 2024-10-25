# AI Healthcare Chatbot

This AI-powered healthcare chatbot project is designed to provide preliminary health assessments based on user-inputted symptoms. Utilizing machine learning algorithms and natural language processing (NLP), the chatbot predicts possible health conditions, offers descriptions, and suggests precautionary steps. This project is intended for educational purposes and should not replace professional medical advice.

## Project Structure

The project is organized into the following folders and main files:

### 1. Folders

- **Data**
  - **dataset.csv**: The primary dataset containing symptoms and associated diagnoses, used to train the chatbot’s predictive model.
  - **Training.csv**: A subset of `dataset.csv`, specifically used for training the Decision Tree model.
  - **Testing.csv**: A subset for testing the trained model, used to evaluate the accuracy of predictions.

- **MasterData**
  - **Symptom_description.csv**: Contains descriptions of each symptom, enabling the chatbot to give users informative details about their conditions.
  - **Symptom_precaution.csv**: Lists preventive measures for each symptom or condition to help users manage their health better.
  - **Symptom_Severity.csv**: Includes severity levels for symptoms, helping the chatbot assess the seriousness of conditions.

### 2. Main Code File

- **chat_bot.py**: This Python script contains the code for running the chatbot. It loads data from the CSV files, preprocesses the input, trains a machine learning model, and then interacts with users by accepting symptoms as input and responding with potential diagnoses, descriptions, and precautionary steps.

## Features

- **Symptom Recognition and Matching**: The chatbot uses regex-based matching to identify and validate symptoms provided by users.
- **Decision Tree Model for Diagnosis**: Trained on a comprehensive dataset, this model predicts potential diagnoses based on the symptoms.
- **Severity and Recommendations**: The chatbot provides feedback on condition severity and suggests consulting a healthcare provider if necessary.
- **Text-to-Speech Output**: With `pyttsx3`, the chatbot can vocalize its responses, improving accessibility.
- **Detailed Symptom Descriptions and Precautions**: Descriptions, severity ratings, and preventive measures help users understand their symptoms and take informed actions.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/healthcare-chatbot.git



You can copy this code block and save it as `README.md` in your project's root directory on GitHub.
