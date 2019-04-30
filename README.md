# Self Driving car using Deep Learning with Tensorflow.
This is an end to end implementation of the research paper published by Nvidia a couple of years ago, with lots of changes. We will use a Convolution Neural Network architecture to train our model. The link to the original research paper published by Nvidia can be found here: [Nvidia paper](https://arxiv.org/pdf/1604.07316.pdf)


# How to Use the model?
Download the [dataset](https://drive.google.com/file/d/18YHLAJqsZFYNH7spDt5z4Pcml8HpIn3l/view) and extract into the repository folder

Use `python train.py` to train the model

Use `python run.py` to run the model on a live webcam feed

Use `python run_dataset.py` to run the model on the dataset

To visualize training using Tensorboard use `tensorboard --logdir=./logs`, then open http://0.0.0.0:6006/ into your web browser.

# High Level view of the data collection system.
<img src='images/Image01.png'>

# Training the Neural Network.
<img src='images/Image02.png'>

# How the trained network is used to generate steering commands?
<img src='images/Image04.png'>

# The neural network architecture.
<img src='images/Image05.png'>

# Block diagram of the drive simulator
<img src='images/Image06.png'>

# What we see vs what the CNN sees?
<img src='images/Image07.png'>

# Feature usefulness.
<img src='images/Image05.png'>

