# Speaker Recognintion Project

Collaborators: 
@mayakhasarasajii [https://github.com/rahulzach/IIIT-Speaker-recognition/commits?author=mayakhasarasajii]


1. Problem Statement

Speaker recognition systems are in greater demand as a result of the increased reliance on voice-based applications and security systems. Our goal in this project is to use machine learning and Python to create a sophisticated speaker recognition system. In order to replicate real-world situations, the research will incorporate background noise and analyze audio data from five well-known speakers.

To achieve this, the project will leverage the Fast Fourier Transform (FFT) to extract relevant features from the audio data, capturing the frequency components that are essential for speaker identification. The dataset includes recordings of speeches and conversations from the five prominent speakers, alongside background noises commonly encountered in various environments. The machine learning model will be trained on this diverse dataset to learn the distinct features of each speaker, enabling the system to make reliable predictions.

The research being conducted is important because it has the potential to improve voice-based authentication systems, enhance audio recordings by bettering the diarization of speakers, and advance the field of voice-controlled devices.

2. Dataset Details

Our dataset, "Speaker Recognition Dataset - Prominent leaders speeches," was taken from The Speaker Recognition Dataset on Kaggle. It includes speeches from five well-known figures: Margaret Thatcher, Jens Stoltenberg, Benjamin Netanyahu, Julia Gillard, and Nelson Mandela. The speeches of each speaker are arranged into individual files that bear their names. The audio files in these folders are 16000 sample rate, one-second samples with PCM encoding.

The original lengthy speeches were segmented into one-second chunks (0.wav to 1500.wav) for ease of handling, and combining these chunks reconstructs the complete speech for each respective leader. Additionally, a folder named "background_noise" contains non-speech audio clips that mimic ambient sounds found in and around the speaker's environment, such as audience laughter or clapping. These background noises can be incorporated during the training phase to enhance the model's robustness.

To Access the Speaker Recognition Dataset:

https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset/data
