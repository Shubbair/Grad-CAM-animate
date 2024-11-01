# GradCAM

> GradCAM (Gradient-Weighted Class Activation Mapping)

Technique show heatmap of interest region that CNN model focuses on through conv-layer activations.

**Cons** : works with All CNN architecture models

**Architecture**  
![arch](assets/grad_cam.png)

Original Image :  
![original](assets/1.png)

Step 1 : Calculate the Grad-CAM  
![raw-gradcam](assets/2.png)

Step 2 : Normalize it  
![normalized-gradcam](assets/3.png)

Step 4 : Add it to the original image  
![final-image](assets/4.png)

Frames shows conv-layer in VGG-19 Model activation for the Dog image :  
![animate-gradcam](assets/grad-cam-animate.gif)

## Reference

[Grad-CAM paper](https://arxiv.org/pdf/1610.02391)
