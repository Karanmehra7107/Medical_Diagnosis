# Medical_Diagnosis

__Capstone-2: LPU | CAP347 CARGC0019__


![Pyhon 3.4](https://img.shields.io/badge/ide-jupyter_notebook-blue.svg) ![CSS](https://img.shields.io/badge/design-CSS-brightgreen.svg) ![Bootstrap](https://img.shields.io/badge/code-Bootstrap-purple.svg)  

## Table of Content
  * [Problem statment](#Problem-statment)
  * [Screenshots](#screenshots)
  * [Demo](#demo)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Directory Tree](#directory-tree)
  * [Team](#team)
  * [License](#license)
  

  • This repository consists of files required to deploy an ___WEB PAGE___ created with ___HTML, CSS, JS, BOOTSTRAP___ on ___github.io___ platform.
  

Flow Chart / archeticture
Why Machine Learning?
Implimentation
ML predictor features
Front-end features
Our resources
Deployment



## About
This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:
* Diabetes
* Breast Cancer
* Heart Disease
* Kidney Disease
* Liver Disease
* Malaria
* Pneumonia

## Models with their Accuracy of Prediction
Disease | Type of Model | Accuracy
--- | --- | ---
Diabetes | Machine Learning Model | 98.25%
Breast Cancer | Machine Learning Model | 98.25%
Heart Disease | Machine Learning Model | 85.25%
Kidney Disease | Machine Learning Model | 99%
Liver Disease | Machine Learning Model | 78%
Malaria | Deep Learning Model(CNN) | 96%
Pneumonia | Deep Learning Model(CNN) | 95%

## NOTE
<br>
==> Python version 3.6.8 was used for the whole project.<br>

## Steps to run the WebApp in local Computer
**Step-1:** Download the files in the repository.<br>
**Step-2:** Get into the downloaded folder, open command prompt in that directory and install all the dependencies using following command<br>
```python
pip install -r requirements.txt
```
**Step-3:** After successfull installation of all the dependencies, run the following command<br>
```python
python app.py
```

or

```python
flask run
```
**Step-4:** Side by side go to the root command prompt run following commands in new cmd terminal<br> 
```
cd templates
index.html
```

Inbulit Debigging mode is on
----------------------
**If already have anaconda prompt base envi..**
```python
flask run
```

## 
## Dataset Links
All the datasets were used from kaggle.
* [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
* [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
* [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
* [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
* [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
* [Malaria Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)
* [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## Links for Python Notebooks used for model creation
* [Diabetes Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Diabetes_Prediction.ipynb)
* [Breast Cancer Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Cancer_Prediction.ipynb)
* [Heart Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Heart_Disease_Prediction.ipynb)
* [Kidney Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Kidney_Disease_Prediction.ipynb)
* [Liver Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Liver_Disease_Prediction.ipynb)




## Team
![breadcumb3](https://user-images.githubusercontent.com/62024355/120712448-44bdb800-c4de-11eb-9d67-edce4e8ef9b7.jpg)


[Karan Mehra](https://karanmehra7107.github.io/My-Portfolio/index.html) | [Surbhi](https://github.com/Surbhisingh014) | [Navdee Nijjar](https://karanmehra7107.github.io/My-Portfolio/index.html)


## License
[![Apache license](https://img.shields.io/badge/license-apache-blue?style=for-the-badge&logo=appveyor)](http://www.apache.org/licenses/LICENSE-2.0e)

Copyright 2021 Karan Mehra | Surbhi | Navdeep

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
