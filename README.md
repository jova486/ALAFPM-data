# ALAFPM-data

This repository contains the necessary files and resources for the study "Anomaly Localization in Audio via Feature Pyramid Matching". The purpose of this study is to localize anomalies in audio files using a feature pyramid matching technique.

## Repository Structure

The repository is organized as follows:

- `Audio_data/`: This folder contains the audio files with added anomalies. The anomalies are provided as ZIP files, named according to the frequency ranges and mixing levels.
- `ground_truth_mel/`: This folder contains the ground truth Mel spectrogram maps, organized in the same manner as the audio files.
- `ground_truth_stft/`: This folder contains the ground truth Short-Time Fourier Transform (STFT) spectrogram maps, organized in the same manner as the audio files.

The files are from the MIMII dataset, specifically the pump -6db id_06 set. All 8 channels have been mixed into mono audio files. This dataset is designed for the study of anomaly localization in audio using feature pyramid matching techniques.



Files with added anomalies:

- 00000841.wav
- 00000812.wav
- 00000723.wav
- 00000245.wav
- 00000579.wav
- 00000691.wav
- 00000684.wav
- 00000367.wav
- 00000809.wav
- 00000424.wav

Files used as normal for testing:

- 00000266.wav
- 00000864.wav
- 00000732.wav
- 00000866.wav
- 00000268.wav
- 00000174.wav
- 00000251.wav
- 00000446.wav
- 00000768.wav
- 00000578.wav

Rest of the set is used for training the model.
