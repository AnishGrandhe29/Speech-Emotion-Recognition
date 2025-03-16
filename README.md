Speech Emotion Recognition Using Random Forest
This project is a Speech Emotion Recognition (SER) system built using Python, librosa, and machine learning (Random Forest Classifier). It processes audio files from the RAVDESS dataset to classify emotions based on extracted features such as MFCCs, chroma, and mel spectrograms. The trained model also automatically segregates audio files based on predicted emotions.

Features
Extracts audio features (MFCC, Chroma, Mel Spectrogram) using librosa
Trains a machine learning model (Random Forest) on a selected actor’s data
Evaluates performance using accuracy score, classification report, and confusion matrix
Predicts emotions on unseen audio samples
Automatically segregates files into directories based on predicted emotion
Dataset
This project is designed for the RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset.

Installation
1. Clone the repository
bash
Copy
Edit
git clone "Paste Link here "
cd speech-emotion-recognition

3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt

5. Run the script
Modify the dataset path and the actor to train on in main.py, then execute:

bash
python main.py

Results
Model performance is displayed via classification reports and a confusion matrix
Audio files are automatically moved into categorized folders based on the predicted emotion

Requirements
See requirements.txt for required dependencies.
