# MNIST Character Recognition Neural Net
***
## Three Layer Neural Network Trained on the MNIST dataset to recognise human handwritten numbers
***
### 1. Intro
This neural network is written following lessons from a great ML book for beginners,
[Make Your Own Neural Network](https://www.amazon.com/Make-Your-Own-Neural-Network/dp/1530826608), by Tariq Rashid.

This simple but powerful three-layer neural network is trained on data from the MNIST Dataset.

### 2. Dataset
The dataset used is the MNIST Dataset reformated to *.csv*.
This project contains only a hundred training examples and ten test cases in the *mnist_train_100.csv* and *mnist_test_10.csv* files respectively. These are located in the *mnist_dataset* directory.

However, the code in the *main.py* was last trained on the full 60,000 training examples file and tested on the 10,000 test case file that you can download from [here](http://pjreddie.com/media/files/mnist_train.csv) and [here](www.pjreddie.com/media/files/mnist_test.csv) respectively.

You should place these files in the *mnist_dataset* folder before running the code.
Adjust the learning rate, number of epoch, hidden nodes or other variables to experiment.

### 3. Results
I managed to attain an accuracy rate of around 97.48% with the following parameters:
    `hidden_nodes = 200`,
    `learning_rate = 0.1` and `epochs = 5`.