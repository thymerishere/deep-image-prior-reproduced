# Deep Image Prior Reproduced
This project contains an experiment for the reproducibility project report in deep learning course (CS4240) at Delft University of Technology which analyses the results from the [Deep Image Prior paper by Ulyanov et al.](https://dmitryulyanov.github.io/deep_image_prior). We replicate the results using their provided code, analyse the results and go more in depth by analysing the effect of hyperparameter tuning, network modifications and different images.

In order to run this expirement, which is contained in a Jupyter Notebook, first download the [original Deep Image Prior project from github](https://dmitryulyanov.github.io/deep_image_prior) and put the folder in the root of your Google Drive. Then download the `custom` folder, which contains a custom dataset used in our experiment, and put it inside `deep-image-prior-master/data`. Then the Jupyter Notebook can be opened in Google colab and further steps will be explained within.

The results of the original paper were successfully reproduced and analysis showed that the results are very sensitive to hyperparameter changes and good results depends on a good choice of hyperparameters. Furthermore, skip connections are shown to allow for better results.
