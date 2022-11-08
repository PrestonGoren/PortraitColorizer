# PortraitColorizer
Completed as part of CAP5404 Deep Learning for Computer Graphics

This notebook trains two models on a dataset of portrait images in l,a,b format. The first model (regressor) is given as input a grayscale image (the l channel) and attempts to predict the mean a and b channels (ignoring pixel location) of the given image. The second model (colorizer) is also given as input a grayscale image, but attempts to reconstruct the a and b channels of the image in their entirety.

Further details and explanation can be found in the ColorizerReport.pdf file.
