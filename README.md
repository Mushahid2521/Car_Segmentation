## Car Segmentation
This project is motivated from this [Kaggle Competition](https://www.kaggle.com/c/carvana-image-masking-challenge). This is basically a segmentation problem. Here I have used [UNet](https://arxiv.org/abs/1505.04597) network architecture which do extremely well in medical segmentation tasks. The datasets can be found [here](https://www.kaggle.com/c/carvana-image-masking-challenge/data).
![Unet Architecture](https://github.com/Mushahid2521/Car_Segmentation/blob/master/Unet_architecture.PNG)

The network is designed using Keras framework. I have taken help from [this notebook](https://www.kaggle.com/keegil/keras-u-net-starter-lb-0-277/notebook) to build and the keras model. All the code description is present in Ipython notebook file.

Here is one of the test image result:



![Image](https://github.com/Mushahid2521/Car_Segmentation/blob/master/image.PNG) ![mask](https://github.com/Mushahid2521/Car_Segmentation/blob/master/mask.PNG) ![masked car](https://github.com/Mushahid2521/Car_Segmentation/blob/master/mask_img.png)

