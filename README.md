# Machine Learning approaches to User Intent Detection

We introduce two possible Machine
Learning approaches to address the problem of intent detection.
The solution compares different classification models: Random
Forests and Support Vector Machines. By leveraging both time
and frequency-based features of the audio files, both models
achieve promising results.

Intent detection aims to recognize the action that the user
wants to perform. The proposed task focuses on classifying
the user’s intent, given a dataset of spoken utterances. The
dataset consists of two parts:
- Audio files: audio samples in .wav format
- Metadata: files .csv that contain information about each
audio sample in the dataset and about its speaker.

The dataset provided is composed of 11,309 recordings (.wav)
of user queries with English pronunciation. The metadata have
been distributed in two separate collections:
- a development set, containing 9,854 records of recordings
for which the intent is known;
- an evaluation set, containing 1,455 records of recordings
without the target variable.

We used the development set to build a classification model
capable of classifying user intentions for each record of the
evaluation set.
