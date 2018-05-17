# Driver-Distraction-Detection-using-ML

--------------------------------------------------------Important-------------------------------------------------------------
# Distracted Drivers Starter Project
This starter project currently ranks in the top 15% of submissions and with a few minor changes can reach the top 10%.

## Dataset Source
The dataset will be downloaded from kaggle's website.

### Dataset Preparation

1. Download the images and drivers list into the "dataset" folder:
2. Unzip both into the "dataset" folder so it looks like this:
  - distracted-drivers/
    - dataset/
      - imgs/
        - train/
        - test/
      - driver_imgs_list.csv

### Running
This project uses [TensorFlow].
To run the code locally simply install the dependencies and run `python main.py`.

## Model Development
1. Tune your learning rate. If the loss diverges, the learning rate is probably too high. If it never learns, it might be too low.

2. Good initialization is important. The initial values of weights can have a significant impact on learning. In general, you want the weights initialized based on the input and/or output dimensions to the layer (see Glorot or He initialization).

3. Early stopping can help prevent overfitting but good regularization is also beneficial. L1 and L2 can be hard to tune but batch normalization and dropout are usually much easier to work with.
