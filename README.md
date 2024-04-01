## Overview
This project implements the deep learning model proposed by Liu et al. for diagnosing arrhythmia using ECG signals, as detailed in their research paper. 
Arrhythmia, a heart condition characterized by abnormal electrical impulses, can significantly hinder blood circulation, potentially leading to heart attacks or strokes. 
Traditional arrhythmia detection methods rely on pre-processed, denoised ECG signals, which may not preserve crucial signal features. 
This project leverages the power of deep learning, specifically the attention mechanism, to process raw ECG signals directly, 
potentially improving diagnostic accuracy by focusing on the most relevant signal parts.

## Model Description
The core of our implementation is the attention-based deep learning model. 
The attention mechanism within the model assigns weights to different slices of an ECG signal based on their importance, 
hypothesizing that significant peaks in the ECG signal, indicative of potential arrhythmias, will be weighted more heavily than noisy segments. 
This allows the convolutional neural network (CNN) to focus on the most informative parts of the ECG signal for diagnosis.

## Dataset
The ECG data used to validate our model comes from the MIT-BIH Arrhythmia Database available on the MIT-BIH website. 
This dataset is widely used for benchmarking algorithms in the field of arrhythmia detection and consists of various annotated ECG signals representative of 
different heart conditions.
