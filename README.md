# CNN-MNIST
A CNN implementation on the MNIST dataset in Tensorflow  that gives accuracy of 99.35%.

This particular implementation follows that given in tensorflow official website.

It uses 2 layer convolution network, max-pooling and a dropout layer.The optimiser used in this CNN is an ADAM optimiser to minimize the cross-entropy. 

The accuracy achieved is of 99.35% on training on 60000 data. The training time was around 2 hours in Intel Core i5 processor and 8 GB of RAM. 
A lesser accuracy of 99.29% was obtained on training on 20000 data on the same system that took 30 mins. 

If you want an faster outcome feel free to rum with 20000 data instead of all 60000.

To run this file. download the repo and enter the following in the terminal,

```
$python3 mnist.py
```
To run this file offline, download the MNIST dataset from "http://yann.lecun.com/exdb/mnist/" and keep the files in a folder MNIST_data at the same folder as input_data.py and mnist.py which is set as the default path.

Best of luck!
