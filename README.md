Welcome to my Data Analytics Portfolio where I showcase my various projects ranging from my university's library data occupancy analysis to vizualizing HIV incidence data. 

# [Project 1: Analyzing library data occupancy data](https://github.com/normatovbekzod/library_data_analysis)
## Aim: 
### Analyze Yale-NUS library occupancy data in order to reveal insights into when the library is the busiest and which sections of the library are under-used.
## Objectives:
 - create a data collection method that can be used by students working for the library
 - clean data using R
 - prepare data for analysis by exporting it in excel format
 - analyze occupancy data using excel and R
 - data vizualizations using excel
 - a monthly report with key insights and findings
 - find out which library areas are under-used by analyzing the popularity of each seat (based on occupancy count)
 
## Data collection
Data is collected hourly during library opening hours by students working for the library by manually filling in the qualtrics form. This data collection method is secure as only those with password to the form could collect data; however, it is also prone to human errors. The dataset is also secure on the qualtrics website and raw data could be downloaded in the csv format. 

## Data processing
In order to process raw data, R was used. Data processing step involvs declaring a number of functions that help turn raw data into proper and easily understandable parameters. This step involved handling missing data, checking for outliers, which usually indicated a human error during data collection and checking for duplicates. Processed data was then exported into the excel file.

## Data Analysis and Visualizations
Data analysis involved performing a number of EDAs and visualizing occupancy counts in various sections of the library throughout the day and how some of the metrics such as average occupancy on weekends and weekdays compares to other months. 
Below are two examples of such visualizations. 
<p align="center">
  <img width="600" height="400" src="image/total_weekday.PNG">
  <img width="600" height="400" src="image/total_weekend.PNG">
</p>

## Reporting and Actions
Main insights and vizualizations are included in a monthly report prepared at the start of following month. This report is saved in the Microsoft word format and shared with the library managers. 

# [Project 2: Global COVID-19 vaccination tracker](https://public.tableau.com/app/profile/bekzod.normatov/viz/Global_vax_tracker_2021/GlobalVaccineTracker)
At the end of 2021 I was back home in Uzbekistan and was unpleasantly surprised to find out that my family and friends believed that most of the people in the world are not getting vaccinated and it is only the minority that agrees to get one dose of the vaccine let alone both doses. I could see where they were coming from as the vaccination program in Ubekistan was very slowly rolling in. As a result, I wanted to create a dashboard where my family and friends could see how the world is giving into the idea of getting vaccinated by visualizing some metrics and plots such as share of the total population that received one or two doses by country, region. 

# [Project 3: Sentiment Analysis of movie reviews using nltk data](https://github.com/normatovbekzod/movie_reviews)
The goal of this project is to train a model that would predict whether a given movie review is position or negative.
- Dataset was taken from nltk movie reviews dataset
- The dataset was split into training and testing sets
- Algorithm used: K-nearest means, TF-IDFs, Singular Value Decomposition(SVD)
- Accuracy rate achieved: 80.6%

# [Project 4: Data visualization of HIV incidence per 100000 in difference regions of Uzbekistan](https://github.com/normatovbekzod/hiv_by_uzb_region)
I have volunteered at the national AIDS and HIV center in Tashkent, Uzbekistan. Through this expereince I had an opportunity of raising awareness of HIV prevelance in different parts of Uzbekistan and advocate for better transperancy and ananimity of the data on hiv infections. 

<p align="center">
  <img width="650" height="400" src="image/hiv_by_region_2022.PNG">
</p>
