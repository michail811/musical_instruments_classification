Musical Instrument Classification

This project focuses on classifying musical instruments using audio data. The dataset is sourced from Philharmonia, and the classification task involves recognizing instruments such as cello, flute, oboe, saxophone, trumpet, and viola.

Techniques and Features
Data Loading and Preparation:

Importing essential libraries for audio processing and machine learning.
Exploring the dataset structure and creating a list of audio files.
Data Labeling:

Determining the number of audio files for each instrument class.
Assigning labels to the audio files based on instrument classes.
Labels Encoding:

Using scikit-learn's LabelEncoder to convert instrument labels into numerical representations.
Signal Processing and Feature Extraction:

Defining signal processing and machine learning parameters.
Extracting features from audio data, including Mel spectrograms and MFCCs.
Normalizing audio waveforms and calculating feature vectors.
Visualization:

Visualizing audio waveforms, spectrograms, and MFCCs for different instruments.
Scaling Feature Vectors:

Applying Standard Scaler to scale feature vectors for machine learning.
Data Splitting:

Splitting the dataset into training and testing sets.
KNN Classification:

Utilizing k-Nearest Neighbors (KNN) classifier for instrument classification.
Evaluating performance using metrics like recall, precision, F1-score, and accuracy.
Confusion Matrix:

Generating and visualizing the confusion matrix for a comprehensive performance overview.
