Our Project is an Exploratory Data Analysis project focusing on a major area of concern in community Healthcare: Heart Disease. We are exploring various factors that potentially have an impact on the likelihood a patient suffers from a heart attack and a stroke. Our team found a large dataset, “Indicators of Heart Disease (2022 Update)”, from the website Kaggle. This dataset consists of 2022 annual CDC survey data of over 240,141 adults from all 50 states and has categorical and numerical data on a wide array of factors of a patient’s health status. This dataset was published by Kamil Pytlak and has a CC0:Public Domain license.

Our main question in this EDA project is: Does the region of the United States in which a patient lives play a part in their risk of suffering from a heart attack and a stroke? 

To explore this question, we broke down the dataset into the 4 US census regions: South, West, Midwest, Northeast. For each region we explored what correlations gender, general health, smoking status, alcohol use, and teeth removal impact the likelihood of suffering from a heart attack and/or a stroke, in hopes of understanding which factors are likely more significant with respect to heart attacks and strokes. 

To perform this analysis we used Numpy, Scipy, Matplotlib, and Pandas with python coding in Jupyter Notebook. This dataset primarily included categorical data, so we focused mainly of charts for our analysis.


Through this analysis, we concluded that indeed the region of the United States that a patient lives in does indeed impact their likelihood of suffering from a heart attack or a stroke. This initial analysis shows that gender, general health, and smoking have a higher impact on having a heart attack or stroke in the south but less so in the west. 

The dataset did not include economic or dietary data, which certainly impact one's health and could provide more insight into why the southern states suffered from poorer health outcomes and higher rates of heart attacks and strokes. 




References: 

Indicators of Heart Disease (2022 UPDATE) (kaggle.com)
https://github.com/kamilpytlak/data-science-projects/blob/main/heart-disease-prediction/2022/notebooks/data_processing.ipynb
