# IOT_and_Data_Science_Project
IOT and Data Science Block Project [22E2_5]


<details>
<summary>Portugues</summary>
<br>

[Você pode solicitar acesso do codigo do projeto no colab](https://colab.research.google.com/drive/1Z11KK6HWRgtS7rCMq1hK59FxiHe7rTSZ)
<br><br>
<pre>


# Detecção de câncer de mama
Detecção de câncer de mama usando aprendizado de máquina

<img src="https://cdn-images-1.medium.com/max/2600/1*gNcFEL1cpGpDC4vo1zUAWA.png" />

# O que é câncer de mama?


O câncer ocorre quando mudanças chamadas mutações ocorrem em genes que regulam o crescimento celular. As mutações permitem que as células se dividam e se multipliquem de maneira descontrolada e caótica. As células continuam se proliferando, produzindo cópias que se tornam progressivamente mais anormais. Na maioria dos casos, as cópias das células acabam formando um tumor.

O câncer de mama ocorre quando um tumor maligno (canceroso) se origina na mama. À medida que os tumores de câncer de mama amadurecem, eles podem metastatizar (se espalhar) para outras partes do corpo. A principal via de metástase é o sistema linfático que, ironicamente, também é o sistema primário do corpo para produzir e transportar glóbulos brancos e outras células do sistema imunológico que combatem o câncer por todo o corpo. As células cancerígenas metastatizadas que não são destruídas pelos glóbulos brancos do sistema linfático se movem pelos vasos linfáticos e se instalam em locais remotos do corpo, formando novos tumores e perpetuando o processo da doença.

O câncer de mama não é apenas uma doença da mulher. É bem possível que os homens tenham câncer de mama, embora ocorra com menos frequência em homens do que em mulheres. Nossa discussão se concentrará principalmente no câncer de mama no que se refere às mulheres, mas deve-se notar que muitas das informações também são aplicáveis ​​aos homens.

# O que é câncer de mama?


# O Fatos e figuras

O câncer de mama é o câncer mais comum em mulheres e o segundo câncer mais comum em geral. Foram mais de 2 milhões de novos casos em 2018.

**Prevalência**

1) Ásia
 
    Porcentagem da população mundial: 59
    Percentual de novos casos de câncer de mama: 39
    Porcentagem de mortes por câncer de mama: 44

2) África

    Porcentagem da população mundial: 15
    Percentual de novos casos de câncer de mama: 8
    Porcentagem de mortes por câncer de mama: 12
   
3) EUA e Canadá

    Porcentagem da população mundial: 5
    Percentual de novos casos de câncer de mama: 15
    Porcentagem de mortes por câncer de mama: 9

</pre>

### Libraries used
```python
import numpy as np #for linear algebra
import pandas as pd #for chopping, processing
import csv #for opening csv files
%matplotlib inline 
import matplotlib.pyplot as plt #for plotting the graphs
from scipy import stats #for statistical info
from time import time
from sklearn import tree
from sklearn.model_selection import train_test_split # to split the data in train and test
from sklearn.model_selection import KFold # for cross validation
from sklearn.grid_search import GridSearchCV  # for tuning parameters
from sklearn import metrics  # for checking the accuracy 
#Classifiers 
from sklearn import svm #for Support Vector Machines
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report , confusion_matrix #for Logistic regression
from sklearn.svm import SVC # for support vector classifier
from sklearn.neighbors import NearestNeighbors #for nearest neighbor classifier
from sklearn.neighbors import KNeighborsClassifier # for K neighbor classifier
from sklearn.tree import DecisionTreeClassifier #for decision tree classifier
from sklearn.ensemble import RandomForestClassifier #for Random Forest
```

###How to
To run the scripts you just type:
```python
python script_name.py
```
As result of execution the reached accuracy will print

#### Dataset and Inputs
The characteristics of the cell nuclei have been captured in the images and a classification methods which uses linear programming to construct a decision line. The dataset is published by Kaggle and taken from the University of California Irvine (UCI) machine learning repository.  The data is taken from the Breast Cancer Wisconsin Center. It includes ten (10) attributes taken from each cell nucleus as well as ID and the diagnosis (M=malignant, B=benign).  The dataset has 570 cases and 31 variables.  
* the dataset can be found [here](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)

</details>

---

<details>
<summary>English</summary>
<br>

[You can request access to the project code in colab](https://colab.research.google.com/drive/1Z11KK6HWRgtS7rCMq1hK59FxiHe7rTSZ)

<br><br>
<pre>

# Breast Cancer Detection
Breast Cancer Detection Using Machine Learning

<img src="https://cdn-images-1.medium.com/max/2600/1*gNcFEL1cpGpDC4vo1zUAWA.png" />

# What is Breast Cancer?

Cancer occurs when changes called mutations take place in genes that regulate cell growth. The mutations let the cells divide and multiply in an uncontrolled, chaotic way. The cells keep on proliferating, producing copies that get progressively more abnormal. In most cases, the cell copies eventually end up forming a tumor.

Breast cancer occurs when a malignant (cancerous) tumor originates in the breast. As breast cancer tumors mature, they may metastasize (spread) to other parts of the body. The primary route of metastasis is the lymphatic system which, ironically enough, is also the body's primary system for producing and transporting white blood cells and other cancer-fighting immune system cells throughout the body. Metastasized cancer cells that aren't destroyed by the lymphatic system's white blood cells move through the lymphatic vessels and settle in remote body locations, forming new tumors and perpetuating the disease process.

Breast cancer is not just a woman's disease. It is quite possible for men to get breast cancer, although it occurs less frequently in men than in women. Our discussion will focus primarily on breast cancer as it relates to women but it should be noted that much of the information is also applicable for men.

# Facts And Figures

Breast cancer is the most commonly occurring cancer in women and the second most common cancer overall. There were over 2 million new cases in 2018.

**Prevalence**

1) Asia
 
   Percentage of world population: 59 
   Percentage of new breast cancer cases: 39
   Percentage of breast cancer deaths: 44  

2) Africa

   Percentage of world population: 15
   Percentage of new breast cancer cases: 8
   Percentage of breast cancer deaths: 12
   
3) U.S. and Canada

   Percentage of world population: 5
   Percentage of new breast cancer cases: 15
   Percentage of breast cancer deaths: 9
</pre>

</details>

---

<details>
<summary>Français</summary>
<br>
Français
<br><br>
<pre>



</pre>
</details>

---