# Code Repository for "Analysing the Effect of Temperature in Instance-based
 Contrastive Learning on Imbalanced Data" 
# This repository contains the code used for my Master’s thesis titled "Analysing Effect of Temperature in Instance-based Contrastive Learning on Imbalanced Data." The forked repository includes multiple folders, but only the folder relevant to this thesis has been retained for clarity and efficiency.
-  smallscale directory contains the code to produce our results on CIFARLT  datasets
-  smallscale codes were run on NVIDIA A40
   #Result :
 - cifar10
   begin{tabular}{@{}l *{5}{d{2.2}}@{}}
            \toprule
            & \multicolumn{5}{c@{}}{Temperature \( t_0 \)} \\
           
            & 0.07 & 0.1 & 0.2 & 0.5 & 1.0 \\
            \midrule
            Imbalance Ratio = 0.01 & 45.12 & 45.68 & 44.32 & 40.37 & 34.77 \\
            Imbalance Ratio = 0.02 & 51.19 & 51.42 & 49.79 & 45.92 & 41.6 \\
            Imbalance Ratio = 0.05 & 61.28 & 63.18 & 60.95 & 53.34 & 47.94 \\
            Imbalance Ratio = 0.1 & 72.11 & 73.36 & 71.9 & 62.38 & 55.34 \\
            \bottomrule
        \end{tabular}

Notes
This code has been tested on Python 3.8 with Ubuntu 20.04.

The dataset paths and related configurations need to be updated according to your local setup.


For questions or issues related to this code, please contact me at:

Abhishek Kumar
Email: Abhishekjha3515@gmail.com
