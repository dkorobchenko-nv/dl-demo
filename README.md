# Deep Learning Demo

## Mnist
Tensorflow-based demo for recognition of hand-written digits. Training is performed on the MNIST dataset.
The demo is based on static graph construction.

[mnist_slim.ipynb](mnist/mnist_slim.ipynb) -> Build, train and test the model


## Mnist Eager
Tensorflow-based demo for recognition of hand-written digits. Training is performed on the MNIST dataset.
The demo is based on TensorFlow Eager Executeion (TF >= 1.7)

[mnist_eager.ipynb](mnist/mnist_eager.ipynb) -> Build, train and test the model

## Cat-Dog
Tensorflow-based demo for binary image classification [Cat | Dog]. Training is performed on the ImageNet subset.
The demo is based on static graph construction.

[Tensorflow_train_model.ipynb](catdog/Tensorflow_train_model.ipynb) -> Build and train the model

[Tensorflow_freeze_graph.ipynb](catdog/Tensorflow_freeze_graph.ipynb) -> Freeze Tensorflow graph (prepare for the inference)

[Tensorflow_inference.ipynb](catdog/Tensorflow_inference.ipynb) -> Inference