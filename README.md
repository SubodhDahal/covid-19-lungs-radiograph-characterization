# COVID-19 Characterization on Lung Radiographs

Using Deep Learning for categorizing radiographs of lungs. Implemented for Coding.Waterkant hackathon as a part of [Waterkant Festival](https://waterkant.sh/) June 2020.

## Description

In the current critical situation of COVID-19 spread throughout the world appropriate image assessment can help to optimize treatment for patients admitted to hospitals. Currently imaging by x-ray radiography is standard, in uncertain cases with CT. 

Patterns typical for COVID-19 commence with predominantly peripheral 
ground glass opacities visible on CT, followed by interstitial changes 
and consolidations that can become extensive at later disease stage, 
associated with a poor prognosis. Radiographs are less sensitive and 
specific compare to CT but still contain valuable information [(W. Liang et al., JAMA 2020)](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2766086). Imaging may help improve patient stratification, e.g. predicting a poor outcome.

## Implementation details

Used transfer-learning in Tensorflow. Experimented with VGG16, InceptionV3 and Xception model trained on ImageNet.

## Dataset

For training and validation of the networks a dataset of radiographs from a pre COVID-19 time [Kaggle Chest X-ray Competition (Pneumonia](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia?)) was used. This included 3883 cases with pneumonia and 1349 healthy controls.