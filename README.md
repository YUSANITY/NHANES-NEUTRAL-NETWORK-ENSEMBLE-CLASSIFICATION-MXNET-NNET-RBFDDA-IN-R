# NHANES NEUTRAL NETWORK ENSEMBLE CLASSIFICATION MXNET NNET RBFDDA IN R  #
## 1.0 BUSINESS UNDERSTANDING ##
### 1.1 Problem Description ###
An estimated 790,000 United States (US) adults suffer from myocardial infarction also known as heart attack each year which suddenly denied oxygenated blood from reaching the heart muscle. (Elizabeth, 2017) If the condition is not treated promptly, permanent heart damage or even death ensues. 
However, one in every five heart attack hits the victim when they least expected, which suggests that they often are not render with proper treatments and had acted on early warning risk signs. (Benjamin, Blaha, Chiuve, Cushman, Das and Deo, 2017)
Therefore, the team intend to develop a model that can identify the prevalent factors that can successfully predict a heart attack so that the authority can pick up the subjects at risk and develop programs that can mitigate the risk conditions. 
The targeted outcome is to reduce the heart attack rate of US adults by 10% in 10 years.

### 1.2 Business Objective and Goals ###
The team will be using the self-reported datasets from the National Health and Nutrition Examination Survey (NHANES) which provides a unique statistical representation of the country population’s personal information, general health, habits and diet. (NCHS, 2018) 
We hope to extract information to gain insights on the tell signs of the heart attack patients that would be usefully for us to predict who are at risk of suffering from a heart attack.   
### 1.3 Methodology ###
The team will be using Cross-Industry Stand Process for Data Mining (CRISP-DM) methodology to systematically structure the data mining processes. It consists of six phrase which are Business Understand, Data Understanding, Data Preparation, Modelling, Evaluation and Deployment. 
As the selected datasets are complex and may have nonlinear relationships between dependent and independent variables, we will be employing Neutral Networks (NN) to model the problem domain. Since our objective is the prevention and not the diagnosis of heart attack, we can mitigate the disadvantages of the “Black Box” nature mentioned by Tu (1996) that plagued neural network model adoption in predicting medical outcome. 
The R package CARET (Classification And REgression Training) provided the functions to streamline the neural network model training, testing and building of the ensemble. 
We will train a single layer perceptron model from NNET library, multi-layer perceptron model from MXNET library and radial basis function with dynamic decay adjustment algorithm model from RSNNS library in R. 
Lastly, we will utilise the caretStack function from the caretEnsemble library with K-nearest neighbour algorithm in R to create the ensemble of the three NN model for the final predication. 


## 2.0 REPORT ##
Please refer to PDF report for more information. 
