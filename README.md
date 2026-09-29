I used cv2.imread() to read the images. I used cv2.resize() with interpolation method of cv2.INTER_AREA to resize the image. It worked fine.
I tried ommiting the Flattening step but it did not work out. The data needs to be unrolled into a single 1D vector so that it can be fed into the fully connected (Dense) layers.

A single convolutional layer performed poorly. Adding 3 convolutional layers improved the model performance.
