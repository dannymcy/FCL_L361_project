# FCL_L361_project
This work is done in the final project of L361 by Chenyang Ma and Yuwei Zhang.

All the code and included in `L361_Project.ipynb`. The starting code is based on Lab 2 of the L361 course. The notebook can also be accessed through the [link](https://colab.research.google.com/drive/1K77dGJ-UbJfcBQppnGveB68as27K2M-L?usp=sharing) here.

Our project report can be found in `report.pdf`.

In the notebook, the data and all required libraries are included or generated, so you do not need to setup a virtual environment in order to run the code. We first implement the techniques including EWC, (A)FTA, KD. Then we first test (A)FTA on the conventional FL setting using the natural partition of FEMNIST dataset.

Then we set up the federated continual learning setting by creating two datasets based on FEMNIST. Permuted-FEMNIST and Split-MNIST. The detailed explaination can be found in the report. We run comparitive results of vanilla CNN, CNN-FTA, CNN-AFTA, both with and without combining other CL techniques (KD and EWC). The final results are included in `PermutedMNIST/5-Task 10-class Comparisons` and `SplitFEMNIST/Domain-IL Comparisons`.

