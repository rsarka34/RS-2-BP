# RS-2-BP

**RS-2-BP: A Unified Deep Learning Framework for Deriving EIT-Based Breathing Patterns from Respiratory Sounds**

**Authors: Arka Roy, Udit Satija**

# Abstract
<p align="justify">
Respiratory disorders have become the third largest cause of death worldwide, which can be assessed by one of the two key diagnostic modalities: breathing patterns (BPs) or the airflow signals, and respiratory sounds (RSs). In recent years, few studies have been conducted on finding correlation between these two modalities which indicate the structural flaws of lungs under disease condition. In this letter, we propose `RS-2-BP': a unified deep learning framework for deriving the electrical impedance tomography-based airflow signals from respiratory sounds using a hybrid neural network architecture, namely ReSTL, that comprises cascaded standard and residual shrinkage convolution blocks, followed by feature refined transformer encoders and long-short term memory (LSTM) units. The proposed framework is extensively evaluated using the publicly available BRACETS dataset. Experimental results suggest that our ReSTL can accurately derive the BPs from RSs with an average mean absolute error of $0.024\pm 0.011, ~0.436\pm0.120, ~0.020\pm0.011,~0.134\pm0.068$, and $0.031\pm0.019$, respectively for five different tasks. Furthermore, these derived BPs can be used for extracting different respiratory vitals, identifying disease conditions efficiently, and retrieving salient breathing cycle information from the RSs.
</p>

# Methodology
![EIT_blockdiag_updated2](https://github.com/user-attachments/assets/37aef6dc-79d1-4147-ba80-b2fde0f33091)

