# image-classification
Computer Vision: Building a model with skip connections, assessing its certainty and wrapping it all in a class

I built a model that was trained on a CIFAR10 dataset. The was built by the use of Keras functional API. The infrastructure of the model has skip connections similarly to ResNet models.

I measure the certainty of the model as well. That information gives the information, if we really can trust its results.

All of above is wrapped in a class - a subclass of Model class from Keras.
