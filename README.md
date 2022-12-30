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

7.which weather has the most accidents in USA?

8.Sow the highest accident in USA using Heatmap?
  
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
|City|Shows the city in address field|
|County|Shows the county in address field|
|State|Shows the state in address field|

# Data Cleaning:

In this section, we will clean out our data based on the information retrieved from the previous observations.

Hence, we will have to perform the following subtasks

- Checking for missing values and manipulating them

- Checking the datatypes

- Checking of the Spelling Correction

Its shows that the enormous datas are missing:

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210080464-20ecd99c-1d26-4d2a-9466-4002449285a3.png">
</p>

- Unwanted features are removed by **Table_name.drop(["Feature_name"],inplace=True,axis=1)**

# Exploratory Data Analysis

Exploratory Data Analysis (EDA) is an approach to analyze the data using visual techniques. It is used to discover **trends, patterns, or to check assumptions with the help of statistical summary and graphical representations**.

## 1.what is the top 5 highest accident City and State in USA?

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210081523-d51f261d-a1b5-4195-8f60-74238a6d0eb5.png">
</p>

### Observation:

### Cities:

- From 2016 to 2021, the United States' most accident-prone cities are Miami, Los Angeles, Orlando, Dallas, and Houston.

- Miami has the most elevated pace of incidental with around 105000 and the second-highest city for accidents is Los Angeles.

### States:

Califonia has the huge accident area with around 800000 due to high population and poor traffic controls.

Virgina (va) has the least number of accident with around 150000 among the states in USA.

## 2.How many frequently reported accidents are there in each city?

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210082001-3b7f3e48-70f9-417c-9c98-7158a0886f9b.png">
</p>

### Observation:

The distribution is right-skewed, and more than 70% of accidents occur between 1 and 5000 in each city.

## 3.Which months have the most accidents from 2016 to 2021?

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210082335-9521d587-3e9b-484f-80b4-431a8398ebbf.png">
</p>
  
### Observation:

According to a survey, the harsh weather and business trips to celebrate Christmas and New Year's are to blame for the highest number of accidents in November and December.

In the following analysis, March and April have the fewest accidents, while December has the most, with about 600 000 accidents from 2016 to 2021.

## 4.Which day of the month have the most accients in 2017?
    
<p align="center">
     <img width="800" height="100" src="https://user-images.githubusercontent.com/119164734/210082782-167d7ecf-98df-4c91-aea6-170482cbcf19.png">
</p>

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210082860-ac09e054-fd5b-47a3-ad24-150fbe23e982.png">
</p>
 
                                       





