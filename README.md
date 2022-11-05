# CSR-NET-variations-for-Crowd-Counting
Here I have experimented with 6 different variations of CSR-Net model for crowd counting on Shanghai Tech Dataset. I have tried various 
combinations of optimizers, activation functions along with various epoch rates to see their effects on  crowd counting and density map estimation.
At first the dataset was downloaded from kaggle and preprocessing was done to shirnk size and generate density map. 
The 7 modelsthat we have used for classification of Shanghaitech dataset part B is as follows: 
1)Baseline model of CSR-Net (Uses Adam optimizer and SGD activation function)
2) CSR-Lite: It is an architecture similar to CSR-Net with less number of layers.
3) CSR-SGD: CSR-Net with SGD optimizer
4) CSR-Sigmoid: CSR-Net with Sigmoid Activation Function
5) CSR-Sigmoid SGD: CSR-Net with Sigmoid activation function and SGD optimizer
6) CSR_Sigmoid_Adam400 - CSR-Net with Sigmoid activation function and Adam optimizer ran for 400 epoch
7) CSR-Sigmoid_BinaryCrossEntropy -  CSR-Net with Sigmoid activation function and Binary Cross Entropy Optimizer
