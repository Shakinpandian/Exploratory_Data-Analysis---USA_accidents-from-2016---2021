# Exploratory_Data-Analysis---USA_accidents-from-2016---2021

<p align="center">
     <img width="400" height="200" src="https://user-images.githubusercontent.com/119164734/210074112-12486a95-cdab-4cf9-a242-10cf2368d5c7.jpg">
</p>

# Problem Statement:

The economic and societal impact of traffic accidents cost U.S. citizens hundreds of billions of dollars every year. And a large part of losses is caused by a small number of serious accidents. Reducing traffic accidents, especially serious accidents, is nevertheless always an important challenge.
 
To find out from the given data:

1.what is the top 5 highest accident City and State in USA?

2.How many frequently reported accidents are there in each city?

3.Which months have the most accidents from 2016 to 2021 ?

4.Which day of the month have the most accients in 2017?

5.Which weekday have the most accident in USA?

6..Which hour the most accients obtained in USA from 2016 to 2021?

7. which weather has the most accidents in USA?

7.Sow the highest accident in USA using Heatmap?
  
# Importing Libaries Package

The following libaries and tools are used in the project.


<p align="center">
     <img width="400" height="200" src="https://user-images.githubusercontent.com/119164734/210078332-6fed5ad6-2712-4e12-bb53-d48722cd36ab.png">
</p>

**Pandas**: Importing for panel data analysis

**Numpy**: For numerical python operations

**Matplotlib (Pyplot)**: A popular plotting library used along with pandas

**Seaborn**: A library, built on matplotlib, to create beautiful plots

**folium**: Visualization by Map

# Loading Data

The dataset has been collected from the **Kaggle.Com** and the dataset in Excel format.

To load the data **pd.read_csv("data//path")**.

**From the data 2845342 rows and 48 features are gained**.


Data Description:

| Features | Description |
|---|---|
|Severity| Shows the severity of the accident|
|Start_Time|Shows start time of the accident in local time zone|
|End_Time|Shows end time of the accident in local time zone|
|Start_Lat|Shows latitude in GPS coordinate of the start point|
|Start_Lng|Shows longitude in GPS coordinate of the start point|
|End_Lat|Shows latitude in GPS coordinate of the end point|
|End_Lng|Shows longitude in GPS coordinate of the end point|
|Weather_Condition|Shows the weather condition (rain, snow, thunderstorm, fog, etc.)|
|Wind_Speed(mph)| Shows wind speed (in miles per hour)|
|Sunrise_Sunset|Shows the period of day (i.e. day or night) based on sunrise/sunset|

