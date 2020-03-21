# CamVid-Image-Segmentation
 Performing Image Segmentation on the CamVid Dataset images
 
 Library used: **Fastai**
 
 We haved used **U-net** as our architecture.
 
 We first train the network on images whose sizes are half of that of the original images in the CamVid Dataset. We then take this trained model, and fit it  on the original images of the Dataset, which helped to increase the accuracy significantly. This is called **Progressive Resizing**.
