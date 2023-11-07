## How Does Regionality Affect Health Outcomes?: An Exploratory Data Analysis Project 
Our Project is an Exploratory Data Analysis project focusing on a major area of concern in community Healthcare: Heart Disease. We are exploring various factors that potentially have an impact on the likelihood a patient suffers from a heart attack and a stroke. Our team found a large dataset, “Indicators of Heart Disease (2022 Update)”, from the website Kaggle. This dataset consists of 2022 annual CDC survey data of over 240,141 adults from all 50 states and has categorical and numerical data on a wide array of factors of a patient’s health status. This dataset was published by Kamil Pytlak and has a CC0:Public Domain license.

Our main question in this EDA project is: Does the region of the United States in which a patient lives play a part in their risk of suffering from a heart attack and a stroke? 

To explore this question, we broke down the dataset into the 4 US census regions: South, West, Midwest, Northeast. For each region we explored what correlations gender, general health, smoking status, alcohol use, and teeth removal impact the likelihood of suffering from a heart attack and/or a stroke, in hopes of understanding which factors are likely more significant with respect to heart attacks and strokes. 

![Picture1](https://github.com/anelaherandez/Project_1_Team7/assets/144189200/33ead3df-f030-4750-928f-83eeef4df297)

To perform this analysis we used Numpy, Scipy, Matplotlib, and Pandas with python coding in Jupyter Notebook. This dataset is very large and has a plethora of categorical and numerical data that are primarily studied as indicators of Heart Disease around the globe. As an EDA project, we limited our scope to just analyzing the heart attack and stroke columns and their accompanying data. Additionally, we split the original dataset into smaller, more manageable csv files by the US census designated regions of the United States. Each member of the group took a region and created a jupyter notebook to perform analysis. Daniela took the Northeast and Midwest, Andrea took the South, and Ryan took the West. The first step in all of our python data cleaning was to transform the categorical data into integer data for ease of analysis. Then we focused on each of the factors of interest to see the significance each played in a patient suffering from a heart attack or stroke. 


## Conclusions and Limitations
Through this analysis, we concluded that indeed the region of the United States that a patient lives in does indeed impact their likelihood of suffering from a heart attack or a stroke. This initial analysis shows that gender, general health, and smoking have a higher impact on having a heart attack or stroke in the south but less so in the west. 

![history of heart attack_gender](https://github.com/anelaherandez/Project_1_Team7/assets/144189200/de1a6255-b7e2-40ec-b9ac-cb55c662cecf)



The dataset did not include economic or dietary data, which certainly impact one's health and could provide more insight into why the southern states suffered from poorer health outcomes and higher rates of heart attacks and strokes. 




References: 

Indicators of Heart Disease (2022 UPDATE) (kaggle.com)
https://github.com/kamilpytlak/data-science-projects/blob/main/heart-disease-prediction/2022/notebooks/data_processing.ipynb
