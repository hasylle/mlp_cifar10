# mlp_cifar10
Using 3-layer MLP on CIFAR10 dataset

Test accuracy: 52.2%

This is the best accuracy I got after experimenting with a few combinations of these parameters: hidden units, activation layer, dropout, and optimizer. The images have a lot of features we need to extract so we cannot expect just a 3-layer MLP to perform well in this classification problem. 52% is good enough after these limitations.
