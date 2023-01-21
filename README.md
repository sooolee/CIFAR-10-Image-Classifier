# CIFAR-10 Image Classifier

In this project, I build a neural network of my own design to evaluate the CIFAR-10 dataset. The goal is to achieve an accuracy greater than 70%. 

I use PyTorch to build the model. I chose to use Resnet50 and retrain its fully connected layers.
- Size of Train Dataset: 50000
- Size of Test Dataset: 10000
- Batch Size: 64
- Epochs: 2

Training losses, test losses, and test accuracy are plotted below (every 20 steps).

![losses]

At the end of Epoch 2, the model achieved around 90.7% accuracy (best at 91.1%). Goal Achieved! As shown in the graph above, the losses and accuracy plataued at the end of Epoch 2.

Checkpoint `up2_rn50.pth` is provided. 