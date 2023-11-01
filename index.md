---
# Data Science Portfolio
---
## Machine learning

### Predict Remaining Useful life (RUL) for an Aircraft Engine -Turbo Fan-single pool
 
A turbofan engine is a cirtical component of the aircraft, and monitoring its performance is important to avoid catastrophic failures and expensive downtime.Technologies in condition monitoring have made this possible by using sensors to collet data regarding fault propagation in systems .Machine learning algorithms are useful tools for data analystics modeling .They use features from datasets to detect patterns and build predictive models. The predictive models are then used with new data ,to determine the future reliability of a system by assessing  the extent of degradation from its expected normal operating conditions. This in turn facilitates determination the Reamaining Useful life (RUL) of a system.
#### Dataset 
The NASA dataset contains data on 100 engine degradation that was simulated using C-MAPSS. Each set includes operational settings and sensor measurements (temperature, pressure, fan speed, etc.) for several engines and for every cycle of their lifetime.
#### Output 
Predicted RUL for an Aircraft Engine with 98% accuracy using Deep Learning Classification model (ANN). 

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/vamsicae)

<center><img src="images/Single_pool_engine.png"/></center>

---
### Ball Bearing Remaining Useful Life Estimation using CNN

The data we’ll be using for this project comes from the Prognostics Data Repository hosted by NASA 
We developed a method based on CNN to estimate the level of wear in bearings. First of all, an automatic labeling of the raw vibration data is performed to obtain different levels of bearing wear, by means of the Root Mean Square features along with the Shannon’s entropy to extract features from the raw data, which is then grouped in seven different classes using the K-means algorithm to obtain the labels. 
The raw vibration data is converted into small square images, each of the data representing one pixel of the image.CNN model based on the pretrain VGG16 & Mobile net architecture to classify the wear level and diagnose the rotatory system

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/vamsicaes)

<center><img src="images/Single_pool_engine.png"/></center>

