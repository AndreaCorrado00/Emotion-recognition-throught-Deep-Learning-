# Emotion-recognition-throught-Deep-Learning-

This project focus on predicting emotions and finding possible differences between EEG signals of different subjects when they feel the same emotion. To do it, a dataset of EEG signals is evaluated in different settings, firstly to find the best model to predict emotions and then to exploring the possibility of differences between subject-related signals. The dataset includes time-window features and fft points of the raw EEG signal.

The analysis is done using different models: LSTM and GRU DNN on fft signals, FC DNN on time-window features in the first part of the analysis, then for the second part of the analysis, only LSTM is used.

Analysis shows that in order to predict emotions both fft signals and time-window features are good, without great differences between LSTM or GRU modeling, with better performances for the last one set of features. This first result suggest that using time-window features is probably better to classify emotions. Secondly, LSTM network trained on a subject and then tested on the other one reached good performances, suggesting that there aren't strong differences between subjects when they feel the same emotions.
