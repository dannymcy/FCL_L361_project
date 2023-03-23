# FCL_L361_project
This work is the final project of L361 course by Chenyang Ma and Yuwei Zhang.

All the code is included in `L361_Project.ipynb`. The starting code is based on Lab 2 of L361 course. The notebook can also be accessed through the [link](https://colab.research.google.com/drive/1K77dGJ-UbJfcBQppnGveB68as27K2M-L?usp=sharing) here.

Our project paper can be found in `L361_cm2196_yz798_Project_Paper.pdf`. 

Our presentation is recorded in `L361_cm2196_yz798_Project_Presentation.mp4`, and the slide is `L361_cm2196_yz798_Project_Slides.pdf`.

In the notebook, the data and all required libraries are included and generated, so you do not need to setup a virtual environment in order to run the code. We first implement the techniques including EWC, (A)FTA, and KD. Then, we experiemnt (A)FTA in the conventional FL setting using the natural partition of FEMNIST dataset.

After that, we set up the federated continual learning setting by creating two datasets based on FEMNIST: Permuted-FEMNIST and Split-FEMNIST. The detailed explaination can be found in our paper. We run extensive experiments and compare the results of vanilla CNN, CNN + FTA, CNN + AFTA, combined with one of the three additional CL techniques: none, KD, or EWC. The final results and full training curves are included in `PermutedMNIST/5-Task 10-class Comparisons` and `SplitFEMNIST/Domain-IL Comparisons`.

We also include the checkpoints of all experiments in the `hists` folder.