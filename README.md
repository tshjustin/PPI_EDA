## PPI Dataset 

This repository is for the sole purpose of downloading a simple variation of PPI dataset. Current PPI datasets are hardly documented, thus being hard to understand the featuresa of it. 

The dataset is downlaoded from Spektral - A python deep learning library that also manages datasets, in which the PPI data was taken from there. Since its requires a specific tensorflow version, it is downloaded seperately to prevent compatibility issues in main environment.

The data is cleaned and exported as 3 CSV files for ease of downstream task. 

### Results from EDA 
1. The graph is a single large graph consisting of 56944 Nodes and 818217 Edges.

2. Each node consist of multiple labels - Thus a multi-label classification problem 
