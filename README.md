<img width="1124" alt="Screenshot 2024-10-15 at 10 38 59 PM" src="https://github.com/user-attachments/assets/2e50f7d6-09f4-43e7-bfb3-b7335e7884e8"># RS-2-BP

**RS-2-BP: A Unified Deep Learning Framework for Deriving EIT-Based Breathing Patterns from Respiratory Sounds**

**Authors: Arka Roy, Udit Satija**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rsarka34/RS-2-BP/blob/main/model/RS-BP.ipynb)
[![Paper Link](https://img.shields.io/badge/Paper%20Link-IEEE%20Xplore-green)](https://ieeexplore.ieee.org/abstract/document/10709355)  
[![Paper Link](https://img.shields.io/badge/Preprint-TechRixv-red)](https://doi.org/10.36227/techrxiv.172470166.68738781/v1) 

# Abstract
<p align="justify">
Respiratory disorders have become the third largest cause of death worldwide, which can be assessed by one of the two key diagnostic modalities: breathing patterns (BPs) or the airflow signals, and respiratory sounds (RSs). In recent years, few studies have been conducted on finding correlation between these two modalities which indicate the structural flaws of lungs under disease condition. In this letter, we propose `RS-2-BP': a unified deep learning framework for deriving the electrical impedance tomography-based airflow signals from respiratory sounds using a hybrid neural network architecture, namely ReSTL, that comprises cascaded standard and residual shrinkage convolution blocks, followed by feature refined transformer encoders and long-short term memory (LSTM) units. The proposed framework is extensively evaluated using the publicly available BRACETS dataset. Experimental results suggest that our ReSTL can accurately derive the BPs from RSs with an average mean absolute error of $0.024\pm 0.011, ~0.436\pm0.120, ~0.020\pm0.011,~0.134\pm0.068$, and $0.031\pm0.019$, respectively for five different tasks. Furthermore, these derived BPs can be used for extracting different respiratory vitals, identifying disease conditions efficiently, and retrieving salient breathing cycle information from the RSs.
</p>

# Dataset
BRACETS Dataset:  [![Paper Link](https://img.shields.io/badge/BRACETS%20Data-Mendeley%20Data-red)](https://data.mendeley.com/datasets/f43c7snks5/1)   
![image](https://github.com/user-attachments/assets/91e6c78c-ea29-4ea5-a286-759fe430a97c)

# Methodology
![EIT_blockdiag_updated2](https://github.com/user-attachments/assets/37aef6dc-79d1-4147-ba80-b2fde0f33091)

# Results
<p align="center">

</p>

# Cite as
A. Roy and U. Satija, "RS-2-BP: A Unified Deep Learning Framework for Deriving EIT-Based Breathing Patterns From Respiratory Sounds," in *IEEE Signal Processing Letters*, vol. 31, pp. 2785-2789, 2024, doi: 10.1109/LSP.2024.3475358. 

```bibtex
@ARTICLE{10709355,
  author={Roy, Arka and Satija, Udit},
  journal={IEEE Signal Processing Letters}, 
  title={RS-2-BP: A Unified Deep Learning Framework for Deriving EIT-Based Breathing Patterns From Respiratory Sounds}, 
  year={2024},
  volume={31},
  number={},
  pages={2785-2789},
  keywords={Transformers;Recording;Lung;Convolution;Tensors;Long short term memory;Electrical impedance tomography;Deep learning;Standards;Kernel;Respiratory sounds;electrical impedance tomography;deep learning},
  doi={10.1109/LSP.2024.3475358}}

