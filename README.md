# Unsupervised-Classification-Self-Supervised-

Our project is based on self-supervised learning using constrastive algorithms, where we are trying to implement [Research Paper](https://arxiv.org/pdf/2005.12320.pdf).<br>
For data augmentation we have used tensorflow similarity module.

Note - before running repository on Colab, please change runtime to GPU.

These are the following configurations for which we can use the project - 
1. Changing Dataset (We have used CIFAR10, CIFAR100, SVHN Cropped, and Rock Paper Scissors)<br>
You need to change the dataset name for running the project for the particular dataset and also change the output tensors for softmax.<br>
Example for CIFAR10, you need to change it to 10, and for Rock Paper Scissors you need to change it to 3.
2. Changing Algorithm (We have used SimCLR, SimSiam, and Barlow Twin)<br>
You need to change the algorithm name for running the project for the particular algorithm.
3. Changing epochs and learning parameters for training constrastive model and evaluation model.
