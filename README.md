# AlphaGo

## Overview

#### This project is regarding Classification of Anomalies  in Gastrointestinal Tract through Endoscopic Imagery with Deep Learning. 

#### We use KVASIR dataset which consist of human gastrointestinal (GI) tract endoscopic imagery in order to detect different anomaly types.

#### Our approach was to use Deep Convolutional Neural Network with transfer learning.

#### The dataset consists of 4,000 annotated GI tract images in 8 different classes (different annomalies) where 500 images belong to each class.It contains,

* anatomical landmarks; 
    * z-lines
    * pylorus
    * cecum 

* pathological finding; 
    * esophagitis
    * polyps
    * ulcerative colitis

* polyp removal signs ; 
    * dyed-lifted-polyps
    * dyed-resection-margins.

#### We use MobileNetV2 as our base model

## Setting up the environment

* Install the latest version of python(3.8)

* Install anaconda navigator

* Create a new conda environment

* Active the environment

* Install all the dependencies listed here (You can use either anaconda navigator or CLI)
  
    * Numpy
    * Tensorflow (GPU or CPU version depends on your pc)
    * Keras
    * Matplotlib.

## Dataset
   
   [KVASIR Dataset](https://datasets.simula.no/kvasir/)
    
## Model prediction

I have used kvasir dataset to find the class names of the outputs.So you should know the relative path to the kvasir dataset folder.

```{python}
path ='kvasir-dataset' # Give proper relative path to the data set folder
```
 
* make sure to unzip model.zip file
    
* Open jupyter notebook using anaconda navigator or CLI

* Open prediction.ipynb file using jupyter notebook which is in unzip model folder

* Run cell by cell to make sure free from errors

* Make sure to give relative paths for the KVASIR data set and to predicting image

* After running the final cell you can get a prediction of the image


