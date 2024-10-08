**Gender and Speaker Classification from audio files**

**Part 1: Gender Classification from Audio Files**

Download Data:
Download the dev-clean corpus from https://www.openslr.org/12/.
Understand the structure: directories represent individual speakers, and each directory contains audio files.
A file in the dataset will provide information on the gender of each speaker.

Feature Extraction (MFCC):
Extract MFCC features (Mel-Frequency Cepstral Coefficients) for all audio files using libraries like librosa or python_speech_features.

Data Analysis:
Explore feature distributions, detect outliers, apply normalization, and investigate how features correlate with gender.

Modeling:
Perform gender classification using machine learning models.
Create train and test datasets (ensuring unseen data for testing).
Test at least 4 models: 2 baselines (e.g., logistic regression and decision tree), a neural network, and a CNN.
Report model performance, comparing accuracy between them.


**Part 2: Speaker Classification from Audio Files**

Read Wav2Vec 2.0:
Understand the high-level concepts of wav2vec 2.0. Check the original paper and other resources.

Feature Extraction Using Wav2Vec 2.0:

Download and use the wav2vec 2.0 base model as a feature extractor for your audio data.
Process audio files in 2-second chunks to extract features.

Quantitative and Qualitative Analysis:
Quantitative: Train prediction models for speaker classification, using precision, recall, and accuracy as evaluation metrics.
Qualitative: Apply dimensionality reduction and clustering techniques for visualization of speaker data.
