# Trigger Word Detection

## Overview

This project focuses on developing a trigger word detection system from audio data. Key aspects include:

- **Manual Data Collection**: Collecting and preparing various audio samples for model training and evaluation. Trigger words are represented with 'alexa'.
- **Data Processing**: The collected audio files was preprocessed to ensure consistency. This includes resampling audio to a standard rate, verifying and trimming file durations, and creating a uniform format for input to the model. Background audio segments are combined with trigger and noise samples to create training examples.
- **Model Training**: Implementing a deep learning model using a sequence-based approach.
- **Handling Imbalanced Data**: Applying weighted binary cross-entropy to address class imbalance and preventing overfitting.

## Objectives

- Develop a system to detect specific keywords or phrases in audio signals.
- Utilize sequence models to enhance the detection accuracy.

## References

This code is based on the assignment **'Trigger Word Detection'** from the **Sequence Models** course, which is part of the **Deep Learning Specialization**.
