###  Predicting Cardiovascular Disease Risk based on Smoking Behavior and Demographics

This README provides an overview of our project proposal for predicting cardiovascular disease risk using machine learning techniques.

#### Team: Cody Allison, Alfred Gorvie, Ran Ji

https://docs.google.com/document/d/17M2JwSXApGB4LRJ7sv8cFXm0vfb3J4QmuMZ051Ea3QQ/edit?usp=sharing

#### Introduction:
Cardiovascular disease (CVD) is a major health concern worldwide, causing both morbidity and mortality. One of the most modifiable risk factors for CVD is smoking. However, the relationship between smoking behavior and demographic variables in influencing CVD risk requires further investigation. The proposed project aims to predict the risk of CVD using machine learning techniques based on individuals’ smoking behavior and demographic information. This will help identify individuals at risk of developing CVD and enable early intervention to prevent or delay the onset of the disease.

#### Data Source:
We utilized data from the Behavioral Risk Factor Surveillance System (BRFSS) - National Cardiovascular Disease Surveillance, provided by the Centers for Disease Control and Prevention (CDC). The datasets are available at: 

https://data.cdc.gov/Heart-Disease-Stroke-Prevention/Behavioral-Risk-Factor-Surveillance-System-BRFSS-N/ikwk-8git

https://data.cdc.gov/Survey-Data/Behavioral-Risk-Factor-Data-Tobacco-Use-2011-to-pr/wsas-xwh5

#### Attributes:
Our analysis focused on the following attributes: 

Smoking Behavior: Type (e.g., cigarette, Cessation, E-Cigarette, etc.), MeasureDesc (e.g., Smoking Frequency, Quit Attempt in Past Year Among Every Day Cigarette Smokers, etc)
Demographics: State(Geo Location), Age, gender, ethnicity, education, and others.

#### Technology Stack:
Our project utilized the following technologies:  

Python Pandas: We used Pandas for data manipulation and analysis. 
Spark: We used Spark to handle and process the distributed dataset.
Scikit-learn: We used Scikit-learn for model development and evaluation. 
Tensorflow: We used TensorFlow to design and train our neural network model. 
Tableau: We used Tableau to visuallize outcomes and patterns. 
Matplotlib: We used Matplotlib to plot model performance metrics. 

#### Implementation Plan
Phase 1 - Data Collection and Preprocessing:
Cleanse and preprocess data for consistency and quality.
Split the dataset.

Phase 2 - Model Design and Training:
Design the neural network architecture.
Train the model on the training dataset.

Phase 3 -  Data Model Optimization 

Phase 4 - Data Visualization and Slides

Tableau link:
[https://public.tableau.com/app/profile/ran.ji5107/viz/ML-tabaccoandMCV/Story1?publish=yes](https://public.tableau.com/views/ML-tabaccoandMCV/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

#### Target Performance:
Our target model performance was set at an accuracy of at least 75% in predicting cardiovascular disease risk based on smoking behavior and demographic information.
