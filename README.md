# Deep-Learning-Projects
In this assignment, I will verify the results presented in the paper "Do We Really Need Multiplications in Deep Learning?" by replicating experiments on the CIFAR-10 dataset using VGG, ResNet-20, and ResNet-32 architectures. The focus will be on comparing three approaches: standard Convolutional Neural Networks (CNNs), Binary Neural Networks (BNNs), and Adder Networks (AdderNets).

AdderNets, as proposed in the paper, replace the computationally expensive multiplications in CNNs with additions by using the ℓ1-norm distance to compute similarity between input features and filters, significantly reducing the computational complexity. I will evaluate the performance of these models, with a particular focus on verifying accuracy and computational cost reductions claimed by AdderNets.

The goal is to replicate and confirm the findings from the original research, which demonstrated that AdderNets could achieve competitive accuracy without the need for multiplication-heavy operations in deep learning.

Assignment A8: CIFAR-10 Dataset Overview
In this assignment, I will be using the CIFAR-10 dataset, which consists of 60,000 color images of size 32x32, divided into 10 classes. Each class contains 6,000 images, making the dataset a diverse collection for image classification tasks.

The dataset is split into two primary sections: 50,000 training images 10,000 test images

The training set is further divided into five batches, each containing 10,000 image. These batches are organized in a random order, meaning that some classes may appear more frequently in certain batches than others. However, the total number of images per class across all training batches is evenly distributed, with 5,000 images per class.

The test set consists of one batch of 10,000 images, with exactly 1,000 images randomly selected from each class.

The 10 classes in the dataset are as follows:

Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck
