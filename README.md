# AudioClassificationApplications

DATASET: https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing

I built a model that can classify Capuchinbird sounds. Unfortunately, I couldn't upload it to Github because its size is 4.3 GB.

Firstly, I encode sounds and got their waveforms. Then I transform it into spectrogram to use with CNN. Parameters are so big to train for most GPUs. I used TESLA P100 to train...

loss: 0.0058 - recall: 1.0000 - precision: 1.0000 - val_loss: 0.0017 - val_recall: 1.0000 - val_precision: 1.0000
These are my training results for the last epoch. It lasted 20 minutes to train.
