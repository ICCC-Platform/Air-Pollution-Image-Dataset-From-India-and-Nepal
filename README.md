# Air-Pollution-Image-Dataset-From-India-and-Nepal

**Please Fork and Star our work by visiting our GitHub Repository before using or downloading our dataset**

**1. Forking our repository allows you to create your own copy of our repository, which you can modify and use as you wish.**

**2. Starring our repository is a way for people to show their support and appreciation for our work.**

**https://github.com/ICCC-Platform/Air-Pollution-Image-Dataset-From-India-and-Nepal**

**Introduction:**
This dataset contains images of Air Pollution for different cities in India and Nepal.
The dataset is divided into two folders: Combined_Dataset and Country_wise_Dataset.

Total number of image dataset: 12,240

Image Size: 224*224

**Air Quality Index (AQI) Class and its defination used in the dataset.**

There are a total of six classes of Air Pollution, which we represent in our dataset as follows:

1. Good (0-50): Air quality is considered satisfactory and air pollution poses little or no risk.

2. Moderate (51-100): Air quality is acceptable; however, for some pollutants, there may be a moderate health concern for a very small number of people who are unusually sensitive to air pollution.

3. Unhealthy for Sensitive Groups (101-150): Members of sensitive groups may experience health effects, but the general public is unlikely to be affected.

4. Unhealthy (151-200): Some members of the general public may experience health effects; members of sensitive groups may experience more serious health effects.

5. Very Unhealthy (201-300): Health alert: The risk of health effects is increased for everyone.

6. Hazardous (301-500): Health warning of emergency conditions: Everyone is more likely to be affected.

Reference: 

https://airtw.epa.gov.tw/ENG/Information/Standard/AirQualityIndicator.aspx

![image](https://user-images.githubusercontent.com/111570911/233039078-bc9d5120-d857-48f2-8132-6259ebf68f4b.png)

**Cities of India**

1. ITO, Delhi
2. Dimapur, Nagaland
3. Spice Garden, Bengaluru
4. Knowledge  Park III, Greater Noida
5. New Ind Town, Faridabad
6. Borivali East, Mumbai
7. Oragadam, Tamil Nadu

**City of Nepal**
1. Biratnagar



**Combined dataset:**

The combined dataset folder contains two subfolders.
1. All_img: This subfolder contains all the collected images from all AQI classes.
2. IND_and_NEP: This subfolder contains six different subfolders representing six different classes of AQI.

The csv file in this folder contains all the data and its parameters.
It is labeled as

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class

**Country_wise_Dataset:**

This folder contains two subfolders representing the countries from which the dataset was collected.

1. **India:**
This subfolder contains the subfolder representing the names of all cities from where data were collected.
Each subfolder of cities contains folders representing the data collected for each respective AQI class, as well as a csv file.
which contains the details of each image, like we mentioned above.
Such as,

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class


2. **Nepal:**
We managed to collect the image dataset from Nepal.
This subfolder contains the subfolder representing the name of the city from where data were collected.
This subfolder of the city contains folders representing the data collected for each AQI class and also a csv file.
which contains the details of each image, like we mentioned above.
Such as,

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class

////////////////////////////////////////////////////////////////////////////////

**Dataset Collection Process:**

**1. Visit the site:** The first step in collecting the air pollution data was to personally visit the site. This involved physically going to the location and capturing images and videos of the area.

**2. Note current parameters:** While visiting the site, various parameters related to air pollution were noted. These included measurements of PM2.5, PM10, NO2, SO2, CO, etc. These parameters were noted by referring to publicly available data sources such as the Central Pollution Control Board (CPCB) website. For India we used https://app.cpcbccr.com/AQI_India/  and for Nepal we used: https://www.tomorrow.io/weather/NP/4/Biratnagar/079711/hourly/

**3. Preprocess images:** Once the images and videos were captured, they were preprocessed to remove any images that were blurry, overexposed, or had other quality issues. Only the images that met the desired quality criteria were selected for further analysis.

**4. Extract frames from videos:** In addition to the images, videos were also captured at the site. These videos were processed to extract frames that were suitable for further analysis. Frames that were too blurry or otherwise of low quality were discarded.

**5. Log data:** Finally, all the data collected during the site visit, including the images, videos, and air pollution parameters, were logged in a structured format. 

//////////////////////////////////////////////////////////////////////////////

****Instructions on how to use the AQI image dataset:****

1. Download the dataset from Kaggle and extract the zip file to a folder of your choice. Please Visit this link to download the Dataset:
https://doi.org/10.34740/KAGGLE/DS/3152196

https://www.kaggle.com/datasets/adarshrouniyar/air-pollution-image-dataset-from-india-and-nepal

2. The dataset is divided into two folders: the Combined_Dataset and Country_wise_Dataset. 
Each folder contains subfolders and CSV files.

3. To access the images in the Combined_Dataset folder, go to the folder corresponding to the class of AQI you are interested in.
For example, if you are interested in the 'Unhealthy' class, go to the 'Unhealthy' folder. Inside this folder,
You will find a number of images representing different cities.

4. To access the data in the Country_wise_Dataset folder, go to the folder of the country you are interested in, either India or Nepal.
Inside each country folder, you will find subfolders representing different cities.
Each city folder contains a CSV file that lists the AQI values and other parameters for the city.

5. You can use this dataset to train machine learning models to predict AQI for different cities.
You can also use it for research on air pollution in different cities. For reference to use this dataset you can visit this link: 

https://www.kaggle.com/code/momo88/vgg16-translearning-for-image-based-aqi-estimation

6. If you use this dataset for any purpose, please cite it as the source of the data in any publications or presentations,
resulting from the use of this dataset.

**Citation Request: You can cite our dataset as follows**

APA:

Adarsh Rouniyar, Sapdo Utomo, John A, &amp; Pao-Ann Hsiung. (2023). <i>Air Pollution Image Dataset from India and Nepal</i> [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DS/3152196

Bibtex:

 @misc{adarsh rouniyar_sapdo utomo_john a_pao-ann hsiung_2023,
	title={Air Pollution Image Dataset from India and Nepal},
	url={https://www.kaggle.com/ds/3152196},
	DOI={10.34740/KAGGLE/DS/3152196},
	publisher={Kaggle},
	author={Adarsh Rouniyar and Sapdo Utomo and John A and Pao-Ann Hsiung},
	year={2023}
}

///////////////////////////////////////////////////////////////////////////

**Collected Image Data Distribution for Each AQI Class**
![Data Distribution](https://github.com/ICCC-Platform/Air-Pollution-Image-Dataset-From-India-and-Nepal/assets/111570911/9824eda9-ca14-42f8-ad22-2d6b43577c06)



///////////////////////////////////////////////////////////////////////////

**IMPORTANT!!! It is Instructed to Read our License file before using our dataset.**

///////////////////////////////////////////////////////////////////////////



**Contributors**
1. Adarsh Rouniyar
2. Sapdo Utomo
3. Dr. John A.
4. Dr. Pao-Ann Hsiung


If you have any queries, please do contact us.
1. Adarsh Rouniyar

Email: adarsh@csie.io

2. Dr. John A.

Email: johnmtech@gmail.com 

3. Dr. Pao-Ann Hsiung

Email: pahsiung@gmail.com , pahsiung@ccu.edu.tw 
