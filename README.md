# Style-Transfer-Keras
The work here is based on the neural style transfer in the main repository of Keras github:
https://github.com/keras-team/keras/blob/master/examples/neural_style_transfer.py
The code is modified so that you can do the style transfer on a sequence of images rather than just one image.
Please note that the number of learning iterations for each image is set to 1 as it gives desirable results for most cases, but it is easy to alter the code to learn more than 1 iteration. The base images should be named in the format: [`base_10000.png`, `base_10001.png`, ...].
