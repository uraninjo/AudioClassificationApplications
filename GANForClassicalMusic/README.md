# GANForClassicalMusic

In this model, I have tried to train my model to create a piece of classical music.

I converted tracks to waveforms and waveforms to a spectrogram. In that way, I can train my model with CNN. I thought I can get better results by doing it.

For training, batch_size should be reconsidered for GPUs. Could have been increased or decreased.

You can get better results by increasing the epochs or playing around with settings. For better results or less noisy results generated tensors could be decreased like I did.
