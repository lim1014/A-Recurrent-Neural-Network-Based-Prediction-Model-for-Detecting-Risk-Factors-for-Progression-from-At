# A Recurrent Neural Network Based Prediction Model for Detecting Risk Factors for Progression from Atrophic Gastritis to Gastric Cancer 


>The code and data on this page are for the realization of the paper "A Recurrent Neural Network-Based Prediction Model for Detecting Risk Factors for Progression from Atrophic Gastritis to Gastric Cancer".


## Data
- **Health_checkup_data.csv** : medical check-up data of atrophic gastritis patients from 2002 to 2013 at National Health Insurance Service (NHIS) in South Korea, which is converted as OMOP-CDM was used for this study.
- **DeepPrevention_model.h5** : RNN-based prediction model to find risk factors and to detect high risk group for developing gastric cancer among atrophic gastritis patients
- **DP_result.csv** : DeepPrevantion_model's result csv file

## Code
- **DeepPrevention_RNN.ipynb** : This is a code that can apply **Health_chechup_data** to the **DeepPrevention_model** and result called **DP_result**.
- **DeepPrevention_kmeans.ipynb** : This is a code that executes K-means using **DP_result**.
- **DeepPrevantion_ChiSqaure.ipynb** : This is a code that executes Chi-Sqaure using **DP_result**.


## DeepPrevention Model Plot


 ![model](https://user-images.githubusercontent.com/66989777/122944524-dcfade80-d3b2-11eb-8d65-e36373f00d39.png)
