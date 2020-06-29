# SPTransducPred

Provides Python 3 Implementation of OM and JM-style estimators for transductive prediction as described in the paper Single Point Transductive Prediction: https://arxiv.org/abs/1908.02341. The code provides functionality to reproduce all the experiments/figures in the paper.

In addition to standard dependencies (i.e. numpy/sklearn etc...) the code here parallelizes prediction over the test set for the OM and JM-style estimators using library Ray (https://github.com/ray-project/ray); this can be installed simply using "pip install ray". 

All the experiments herein were run on cluster with 48 cores with 256 GB RAM and we recommend using a cluster with similar compute capacity to speed up the experiments.
