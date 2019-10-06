# Deep Learning Universtiy Assignment Solutions

These are my solutions of the homework assignments from the course 'Deep Learning in practice with python'. This includes the 5 smaller projects that were optional but in the end almost as useful in the learning process as the rest of the course. Please understand that these are some of the first codes I've written for deep learning as such they may contain errors, bad practices and techniques that are simply obsolete at this point. The aim of these projects were to learn the basics of deep learning and its frameworks in Python.

## Getting Started

The only things you'll need to run these notebooks are the imported modules and input pictures for assignment 4 and 5, otherwise they are self contained.

### The projects

Here I'll give a brief explanation of the 5 projects contained in this repository.

#### 1. Python basics
This notebook simply goes throgh the python libraries that are frequently used for data visualization. This doesn't contain anything deep learning related yet.

#### 2. XOR problem
This notebook solves the XOR problem using a simple neural netowrk written without any higher level deep learning framework. The code partly comes from the course and the assignment was to improve the original with mini batches, momentum and regularization (l1, l2).

This was a very important notebook in understanding the basics of a neural network as it forces the user to understand how forward and backpropagation happens on a lower level using only numpy for the computations. It also covers how data should be split for training, validation and testing.

#### 3. Temperature forecasting
The task in this problem was to somehow gather temperature data of the previous couple of years and predict the future temperature on some specific dates. For this I used some simple web scraping methods to collect the data and in the 2nd part of the notebook I use both and LSTM and a 1D convolutional network to make predictions. 

Since at this point I didn't quite understand LSTMs the 1D CNN proved a much better solution for me at the time.

#### 4. Image classification with convolutional network
In the 4th assignment we had to download 600 images of two classes from the Open Images Dataset and train a model that can distinguish between these two classes. This notebook taught me a lot about data preparation for image processing, data augmentation, keras callback functions, and transfer learning as we had to also try out the VGG16 model. 

#### 5. Image generation with DCGAN
In this notebook I attempted to generate images that look like houses using a DCGAN. The last assignment required us to try to generate images with either a variational autoencoder or a GAN and I chose this. Unfortunately I didn't end up with anything satisfactory but it was still a good learning experience. I aim to improve this model later with more data and new techniques.
