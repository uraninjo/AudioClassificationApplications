# AudioClassificationApplications

In this model, I have tried to train my model to detect the sounds of Capuchin Birds.

I converted Capuchin Bird sounds to waveforms and waveforms to a spectrogram. In that way, I can train my model with CNN. I thought I can get better results by doing it.

For training, batch_size should be reconsidered for GPUs. Could have been increased or decreased.

I had 0.0058 loss with good precision and validation losses. The training lasted not very long at TESLA P100. 
