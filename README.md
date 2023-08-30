In this lab, you will build models to perform image colourization. That is, given a greyscale image, we wish to predict the colour at each pixel. Image colourization is a difficult problem for many reasons, one of which being that it is ill-posed: for a single greyscale image, there can be multiple, equally valid colourings.

To keep the training time manageable we will use the CIFAR-10 data set, which consists of images of size 32x32 pixels. For most of the questions we will use a subset of the dataset. The data loading script is included with the notebooks, and should download automatically the first time it is loaded.

We will be starting with a convolutional autoencoder and tweaking it along the way to improve our perforamnce. Then as a second part of the assignment we will compare the autoencoder approach to conditional generative adversarial networks (cGANs).

In the process, you are expected to learn to:

Clean and process the dataset and create greyscale images.
Implement and modify an autoencoder architecture.
Tune the hyperparameters of an autoencoder.
Implement skip connections and other techniques to improve performance.
Implement a cGAN and compare with an autoencoder.
Improve on the cGAN by trying one of several techniques to enhance training.

Due to the file size, the uploaded ipynb file is not run.
