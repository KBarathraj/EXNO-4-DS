# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
       #Developed by BARATHRAJ K (212224230033)
       # INCLUDE YOUR CODING AND OUTPUT SCREENSHOTS HERE
<img width="1653" height="1044" alt="image" src="https://github.com/user-attachments/assets/faea3123-c324-4f92-8f41-1e0e64eccaf7" />
<img width="1640" height="1272" alt="image" src="https://github.com/user-attachments/assets/4908e787-9c19-4fc3-a8b5-b1aa01a9db0e" />
<img width="1640" height="841" alt="image" src="https://github.com/user-attachments/assets/9d4dfc69-4ff9-4255-9d21-b6f895832400" />
<img width="1644" height="773" alt="image" src="https://github.com/user-attachments/assets/2f45cf29-9108-4a7b-aba6-8586fecf9742" />
<img width="1642" height="829" alt="image" src="https://github.com/user-attachments/assets/3615b124-1ce0-466b-bc50-f1e7d84f7369" />
<img width="1645" height="1343" alt="image" src="https://github.com/user-attachments/assets/e6eb3823-31e9-4ee3-9136-1c668f885ddf" />
<img width="1644" height="1039" alt="image" src="https://github.com/user-attachments/assets/cc3c3c90-b899-48b3-8706-067711b8e16b" />
<img width="1634" height="1155" alt="image" src="https://github.com/user-attachments/assets/21cbf883-2027-4a6d-888c-d0b07bc5bbdb" />
<img width="1637" height="713" alt="image" src="https://github.com/user-attachments/assets/00f0dac5-0bd9-43bd-a0bc-45ed2bcf1b4c" />

       
# RESULT:
       Thus we have successfully performed Feature Scaling and Feature Selection on the given data.
