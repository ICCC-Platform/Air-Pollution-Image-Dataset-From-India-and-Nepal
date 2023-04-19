# India-and-Nepal-Air-Quality-Index-AQI-Dataset

***Introduction:***
This dataset contains images of Air Quality Index (AQI) for different cities of India and Nepal.

The dataset is divided into two folders- Combined_Dataset and Country_wise_Dataset.

Total number of images : 12,240

***Combined dataset:***

The combined dataset folder contains two subfolders
1. All_img: This Subfolder contains all the collected image from all AQI classes.
2. IND_and_NEP: This Subfolder contains six different sub subfolders representing six different classes of AQI. 

The csv file in this folder contains all the data and its parameters collected. 
Such as,

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class

***Country_wise_Dataset:***

This folder contains two sub folders representing the counrties from where dataset was collected.

1. India: 
This subfolder contains the sub subfolder representing the name of all cities from where data were collected.
Each sub subfolder of cities contains folders representing the data collected of respective AQI class and also with a csv file
which contains the details of each image like we mentions above. 
Such as,

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class


2. Nepal: 
We manage to collect the image dataset from Nepal.
This subfolder contains the sub subfolder representing the name of city from where data were collected.
This sub subfolder of city contains folders representing the data collected of respective AQI class and also with a csv file
which contains the details of each image like we mentions above. 
Such as,

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class

////////////////////////////////////////////////////////////////////////////////

****Instructions on how to use the AQI image dataset:****

1. Download the dataset from Kaggle and extract the zip file to a folder of your choice.

2. The dataset is divided into two folders - Combined dataset and Country wise dataset. 
Each folder contains subfolders and csv files.

3. To access the images in the Combined dataset folder, go to the folder corresponding to the class of AQI you are interested in. 
For example, if you are interested in the 'Unhealthy' class, go to the 'Unhealthy' folder. Inside this folder, 
you will find a number of images representing different cities.

4. To access the data in the Country wise dataset folder, go to the folder of the country you are interested in, either India or Nepal. 
Inside each country folder, you will find subfolders representing different cities. 
Each city folder contains a CSV file that lists the AQI values and other parameters for the city.

5. You can use this dataset to train machine learning models to predict AQI for different cities. 
You can also use it for research on air pollution in different cities.

6. If you use this dataset for any purpose, please cite it as the source of the data in any publications or presentations 
resulting from the use of this dataset.

///////////////////////////////////////////////////////////////////////////
***Data Distribution of each AQI class***
![Data Distribution](https://user-images.githubusercontent.com/111570911/232965276-6c7e5726-308c-478d-a9cd-3654de8a3835.png)

