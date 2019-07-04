This is a basic example of generating visualisation from a pretrained CNN model
  * a sample CNN trained on fashion_mnist dataset is provided which is used in this example
  * you can replace this model with any model you want to visualise, just remember to change the layer names as per the model you are using. In this example "conv2d_2" is used you need to replace this name with the one you want to visualise
  * this example shows how to visualise the filters and activations as well
  * maximisation of output a layer (maximisation of activations) is also shown, where you start from a random noise image and iteratively change this image to minimise the loss of that layer.
