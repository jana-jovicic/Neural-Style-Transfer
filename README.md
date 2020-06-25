# Neural-Style-Transfer

Neural style transfer is an optimization technique used to take two images, a content image and a style reference image (such as an artwork by a famous painter), and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

Notebook 01_Neural_Style_Transfer.ipynb is based on paper "Image Style Transfer Using Convolutional Neural Networks" by Leon A. Gatys. Style transfer is performed using only two images (content and style image) and pretrained VGG network. Output images are in 01_outputs folder.

Notebook 02_Real_Time_Neural_Style_Transfer.ipynb is based on paper "Perceptual Losses for Real-Time Style Transfer and Super-Resolution" by Justin Johnson. Style transfer is performed by training network for given style on set of images. Then, learned model can be used for applying style transfer on other images in real-time. Output images are in 02_outputs folder and trained models are in 02_models folder.

Example:

![alt text](https://github.com/jana-jovicic/Neural-Style-Transfer/blob/master/reademe_image.png?raw=true)
