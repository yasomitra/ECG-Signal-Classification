Validating "Attention-based CNN" for classification of ECG data

In this project, we have implemented the deep learning model proposed by Liu et al. in their paper for arrhythmia diagnosis using ECG signals. Arrhythmia is a heart condition which causes abnormal electrical impulses in the heart. Such irregularities cause improper blood circulation to the organs all over the body and could lead to heart attacks or strokes.

ECG signals are used to detect arrhythmia, however, the traditional detection techniques require a pre-processed, denoised signal. The methods applied for pre-processing are complex and the resulting signals might not preserve all the important features of the signals. By the advent of deep learning, particularly, the attention layer, the authors have proposed that the detection could be performed using raw ECG signals. The attention layer assigns weight to each slice of the signal, based on its importance. They hypothesise that the peaks would have a higher weight than their noisy counterparts; thus, the CNN could process the weighted information accordingly.

In this notebook, we have validated the model using ECG data from the MIT-BIH website.
