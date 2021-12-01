# leaf-image-classification

This repository is a short description, with notebooks, of the DL Competition organized for the students of the course Artificial Neural Networks and Deep Learning, at Politecnico di Milano.

In this competition we were required to classify images of leaves (like the ones in the example image below), which are divided into categories according to the species of the plant to which they belong. Being a classification problem, given an image, the goal is to predict the correct class label.

![example1](https://github.com/ManuelCecere/leaf-image-classification/blob/main/leaf-image-examples/leaves_example_1.png?raw=true) ![example2](https://github.com/ManuelCecere/leaf-image-classification/blob/main/leaf-image-examples/Leaves_example_2.png?raw=true)

You can find the details and the dataset used for the competition on CodaLab: https://codalab.lisn.upsaclay.fr/competitions/226

The repo contains a report where it's shortly present how my team, Polimi Dropouts, approached the challenge, which was our workflow and the issues we
faced, how we decided to overcome some of them, and finally describe our best models, explaining the rationale of our
choice and the results they produced.

The notebooks included contains the implementation of some of our most successful models, MarkZuckerberg, SteveJobs and BillGates (sorry for the names, the pun with the name of the team was a moral obligation). The BalanceData notebook includes the code used for the preprocessing of the data.

Be careful when running the notebooks. Often, also from the same author, the path to the folders (both for checkpoints, testing, or loading images) changes, due to the fact that we may run the notebook in a different environment. Please, adjust your folder path according to your system. We mainly used Google Colab with Google Drive
