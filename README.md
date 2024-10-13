# Speech-Emotion-Recognition
Speech Emotion Recognition using Deep Learning

This project focuses on the development of a deep learning-based model for speech and emotion recognition. The system is trained to analyze human speech and accurately classify emotions expressed in the audio input. The project leverages advanced neural networks to process speech data and make emotion predictions based on vocal tone and acoustic features.

### Dataset
The dataset used for this project is the Toronto Emotional Speech Set (TESS), which is publicly available on Kaggle. The dataset comprises recordings of two actresses, aged 26 and 64, enunciating 200 target words in the following seven emotional categories:

- Anger
- Disgust
- Fear
- Happiness
- Neutral
- Pleasant Surprise
- Sadness

The TESS dataset is designed to explore how different emotions influence speech and is ideal for training models to distinguish between various emotional states. You can find the dataset here.

## Project Features
1. Deep Learning Model: The project uses deep learning techniques to build a robust model for emotion recognition. It involves preprocessing audio data and training the model using a neural network architecture.
2. Audio Processing: The audio data is processed using libraries such as Librosa for feature extraction, including Mel-frequency cepstral coefficients (MFCCs) and other audio features crucial for emotion classification.
3. Emotion Classification: The model classifies emotions into one of the seven predefined categories (Anger, Disgust, Fear, Happiness, Neutral, Pleasant Surprise, and Sadness) based on the audio inputs.
   
### Frameworks and Libraries:
The project utilizes Python with TensorFlow or PyTorch for model development, along with Librosa for audio analysis and feature extraction. The pipeline includes:
- Data loading and audio feature extraction
- Model training and evaluation
- Performance metrics such as accuracy and loss tracking
- Evaluation and Testing: The model's performance is evaluated using common classification metrics (accuracy, precision, recall, F1-score) to measure its effectiveness in emotion recognition from speech.
