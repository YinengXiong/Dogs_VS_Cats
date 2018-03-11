# Dogs_VS_Cats

<font size=5>__[Dogs_VS_Cats competition](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition)__ on __[Kaggle](https://www.kaggle.com/)<font>__
<font size=5>__Using Transfer Learning__<font>

## Requirements
* __[TensorFlow](https://www.tensorflow.org)__
* __[Keras](https://www.keras.io)__
* __[OpenCV](https://www.opencv.org)__
* __[Scikit-Learn](http://scikit-learn.org/stable/)__

## Results
|   Base Model/Model   | LogLoss  | Ranking |
| :--------:           |     ----:|     --: |
| Inception V3         |   0.04095|      <20|
| Xception             |   0.04101|      <20|
| Inception ResNet V2  |   0.03796|        8|
| Merge                |   0.03582|        7|

![Result on Kaggle](https://github.com/YinengXiong/Dogs_VS_Cats/raw/master/submit.png)

## CAM Visualization
<center>![CAM](./CAM/CAM_pred.png)</center>

<center>![CAM_gif](./CAM/CAM_CAT.gif)</center>

__Jupyter Notebook [here](https://github.com/YinengXiong/Dogs_VS_Cats/blob/master/CAM/CAM%20Visualization.ipynb)__

