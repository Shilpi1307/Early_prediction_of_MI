# Early Prediction of Myocardial Infarction Complication
## Introduction and Description
Myocardial Infarction (MI), also known as a heart attack, is a serious condition that can lead to death. It happens when blood supply to the heart is blocked, which can damage or destroy heart muscle. The risk of MI is high in all countries, but it is especially high in urban areas of developed countries. This is because people in these areas are more likely to be exposed to chronic stress, unhealthy diets, and other risk factors for MI.<br>
The significance of this study lies in its potential to Early and accurate prediction of complications is the key to managing and preventing death due to complications caused by MI.
Most studies do not focus on post-MI complications. In-Hospital Longitudinal analysis of complications not addressed..
An attempt has been made to predict complications of Myocardial Infarction (MI) based on patient information collected at the following four points of time-<br>
time of admission to the hospital<br>
end of the first day (24 hours after admission)<br> 
end of the second day (48 hrs after admission)<br>
end of the third day (72 hrs after admission)<br> 

This study is intended for the effective management of MI so that the lethal outcome may be prevented.

### Dataset
https://archive.ics.uci.edu/dataset/579/myocardial+infarction+complications.
### Functioning of the models
For this research, I have used various machine learning models.<br>
There are four folders in the repository :
1. Early_prediction_mi.ipynb: Contains the preprocessing & models implemented on the dataset.
2. Results: Contains images of the  elbow curve, heatmaps of the clusters of the complications of mi.
3. Methodology: contains the image of the flow of the whole methodology to peform whole study.
### Technologies and libraries used
The contents of this repository were created and implemented in Colab notebooks & jupyter notebook.
The following libraries were majorily used:
1. Pandas
2. numpy
3. Plotly  
4. scikit-learn
5. networkx
6. matplotlib
7. Seaborn
## Contents
1. Introduction and Description
2. Functioning of the models
3. Technologies and libraries used
4. Installations required
5. Running the scripts
6. Using the project
7. License
## Installations
1. To install [Jupyter notebok through Anaconda](https://jupyter.org/install)   
4. To install the required modules:<br>
   ```
   pip install "module name"
   ```
## Running the script
To clone this repository:<br>
   ```git
   git clone "https://github.com/Shilpi1307/Early_prediction_of_MI"
   ```
## Using the project
To use the project :
1. Download the complete datasets from UCI repository.
2. The CSV dataset lacks column headers, so we need to assign names to the columns.
3. Read the csv file and start exloring the dataset try different techniques for preprocessing.
4. after analysing the dataset scale the dataset by using Standard scaler then find out the suitable number of clusters.
5. After the selection of clusters one can find theirs clusters and find the membership of the patients in the each clusters<br> and find out the most relevant feature of the cluster which are contributing towards MI.























