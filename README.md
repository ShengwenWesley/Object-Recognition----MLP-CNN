# Object-Recognition of CIFAR-10 
This ia a walkthrough of typical ML workflow. <br>
Specifically, it starts from Preprocessing dataset with PyTorch utils including transform, Dataset, random_split and Dataloader. <br>
Further, it includes building structure of 3-layer MLP and a simple Convolutional Neural Network with 2 Conv layers. <br>
Following is the construction of training loop with CrossEntropyLoss, Adam optimizer, back-propagation and gradient descent setting up. 
Finally, it comes to validation and testing. 

Due to device limitation, only 30 epochs were run with accuracies of about 50% - 70% in test set for the two simple network. 

## Reference
[1] A. Krizhevsky, “Learning Multiple Layers of Features from Tiny Images,” Apr. 2009. Available: https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf <br>
‌[2] Pytorch, “Training a Classifier — PyTorch Tutorials 1.5.0 Documentation,” pytorch.org. https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
‌
