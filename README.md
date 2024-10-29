# GradCAM

> GradCAM (Gradient-Weighted Class Activation Mapping)

Technique show heatmap of interest region that CNN model focuses on through conv-layer activations.

**Cons** : works with All CNN architecture models

Original Image :
<img src="assets/1.png"/>

Step 1 : Calculate the Grad-CAM
<img src="assets/2.png"/>

Step 2 : Normalize it
<img src="assets/3.png"/>

Step 4 : Add it to the original image
<img src="assets/4.png"/>

Frames shows conv-layer in VGG-19 Model activation for the Dog image : 
<img src="assets/grad-cam-animate.gif" />

## Reference

[Grad-CAM paper](https://arxiv.org/pdf/1610.02391)
