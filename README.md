# Code Repository for "Analysing the Effect of Temperature in Instance-based Contrastive Learning on Imbalanced Data" 
-  This repository contains the code used for my Master’s thesis titled "Analysing Effect of Temperature in Instance-based Contrastive Learning on Imbalanced Data." The forked repository includes multiple 
   folders, but only the folder relevant to this thesis has been retained for clarity and efficiency.
-  smallscale directory contains the code to produce our results on CIFARLT  datasets
-  smallscale codes were run on NVIDIA A40

## Results

Below are the results obtained for different datasets used in this thesis:

### CIFAR-10 Long-Tailed (LT)

| Imbalance Ratio       | \( t_0 = 0.07 \) | \( t_0 = 0.1 \) | \( t_0 = 0.2 \) | \( t_0 = 0.5 \) | \( t_0 = 1.0 \) |
|-----------------------|------------------|-----------------|-----------------|-----------------|-----------------|
| **0.01**             | 45.12           | 45.68          | 44.32          | 40.37          | 34.77          |
| **0.02**             | 51.19           | 51.42          | 49.79          | 45.92          | 41.60          |
| **0.05**             | 61.28           | 63.18          | 60.95          | 53.34          | 47.94          |
| **0.1**              | 72.11           | 73.36          | 71.90          | 62.38          | 55.34          |



### CIFAR-100 Long-Tailed (LT)

| Imbalance Ratio       | \( t_0 = 0.07 \) | \( t_0 = 0.1 \) | \( t_0 = 0.2 \) | \( t_0 = 0.5 \) | \( t_0 = 1.0 \) |
|-----------------------|------------------|-----------------|-----------------|-----------------|-----------------|
| **0.02**             | 23.64           | 23.59          | 21.84          | 16.84          | 13.75          |
| **0.05**             | 30.67           | 29.69          | 26.87          | 20.96          | 16.63          |
| **0.1**              | 36.91           | 36.89          | 33.36          | 25.97          | 20.46          |



Notes
This code has been tested on Python 3.8 with Ubuntu 20.04.

The dataset paths and related configurations need to be updated according to your local setup.


For questions or issues related to this code, please contact me at:

Abhishek Kumar
Email: Abhishekjha3515@gmail.com
collaborator :
Siladittya Manna
Email:  mannasiladittya@gmail.com

Prof  Saumik Bhattacharya

