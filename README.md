# Northern ireland (NI): Brexit, Religion & Reunification  
This project is a part of the Data Analytics Bootcamp Oct 2020 - Jan 2021 at IRON HACK, Berlin, Germany .

I completed this project in 11 days during the bootcamp and was designed to test the knowledge I had gained during the bootcamp. 

This was my first ever larger and independently constructed individual project. I alone decided the entire scope of the project and it therefore is not perfect :).

PLEASE CHECK OUT THE [WIKI](https://github.com/williammollers/finalproject-ironhack-NI/wiki) FOR THIS PROJECT
* Day by day progress
* Limitations explained in detail
* Sources listed in detail

-- Project Status: [Completed]

## Project Objective

The purpose of this project was to analyse RELIGION / VOTING data in Northern Ireland (NI) to see whether these two statements could be clarified:
* Identify electorates in NI that future YES (in a reunification campaign) campaigners should target
* Determine whether there is correlation between religious identity and voting patterns

##### Methods Used

* Kanban (in Trello)
* Data Acquisition (i.e. webscraping)
* Data Exploration / Cleaning / Wrangling 
* Correlation Analysis 
* Data Visualization 
* Presentation 

##### Technologies
* Jupyter Notebook
* Python
* Pandas
* Webscraping
* Numpy
* Excel 
* Tableau
* Powerpoint

## Project Concept

* The concept behind this project was to see whether there is a potential 50%+ majority for a YES vote in any future reunification referendum held in Northern Ireland. 
* The idea for this had come about because of deep personal history (I grew up with a West German father and so understand how painful division is) and the relevance of this topic: even as I type the final negotiations on a Brexit deal are being carried out. 
* Because of the huge amount of data available I decided to limit the project to three main years:

*2011 Census: Data on the religion brought up in
*2016 Brexit Vote
*2019 UK General Election

## Project Description

##### Data Acquisition 

* The data used in this project was acquired from multiple sources, all of which were UK based government agencies. An exact list is [here](https://github.com/williammollers/finalproject-ironhack-NI/wiki/DATA-SOURCES). 

* Most of the data was in XLS format, but sometimes in a huge amount of files, so I needed to iterate over these files to extract what I wanted (see this in the below notebook and the files used are [here](https://github.com/williammollers/finalproject-ironhack-NI/tree/main/ALL_DATA_SOURCES/ORIGINAL/Religion/AA).
Unfortunately the Electoral Office of NI does not provide any data in XLS format and so I had to scrape their website. 

* The entire flow of this can be seen in this [notebook](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/PYTHON/REUNIFICATION_REFERENDUM_IRELAND.ipynb)

##### Data Exploration 

* This was carried out in Excel, as the files were largely in that format. 

##### Data Cleaning 

* I made sure all column names were lower case (mostly)
* Electorate names were harmonised
* A decision was made to keep none values, as they are indicative (e.g. if someone didn't vote or if a party didn't run a candidate in an electorate)

#### Data Wrangling

* I narrowed the scope of the project down to the Electorate level, as I noticed that some data (e.g. all election data) was only provided at that level and subsequently any data that was more granular (e.g. ward level) or more macro (e.g. national) was eliminated from the analysis.  
* I ended up having close to 20 different xls files (some I created myself as in the notebook above) and so I wanted to concatenate them all into 1 or 2 files. 
* I sucessfully did this and so created 2 main sources: 
[my master spreadsheet](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/ALL_DATA_SOURCES/MY_ADDITIONS/MAIN/MASTER_SPREADSHEET.xlsx) and my [voting results spreadsheet](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/ALL_DATA_SOURCES/MY_ADDITIONS/MAIN/ni_uk_19_all_electorates_cian.xlsx)

##### Correlation Analysis

* It is commonly said in NI that if you are Catholic you tend to vote Remain / Republican (reunifying with the rest of Ireland) and if you are Protestant you tend to vote Leave / Unionist (remain with the UK). I wanted to test this. 
* I therefore created two subset xls files here:
[Brexit v Religion](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/ALL_DATA_SOURCES/MY_ADDITIONS/MAIN/CORRELATION_BREXIT_RELIGION.xlsx)
[Religion v Uk General Election 2019](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/ALL_DATA_SOURCES/MY_ADDITIONS/MAIN/CORRELATION_RELIGION_UK_19.xlsx)
* My correlation analysis can be seen in the same [notebook](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/PYTHON/REUNIFICATION_REFERENDUM_IRELAND.ipynb) as above.

##### Data Visualisation

* All data was visualised in tableau and can be seen [here](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/TABLEAU/REUNIFICATION_REFERENDUM_IRELAND.twbx)
* The biggest issue here was joining together many different data sources and I used shape files located here for the [electorates](https://github.com/williammollers/finalproject-ironhack-NI/tree/main/ALL_DATA_SOURCES/ORIGINAL/Westminster_Parliamentary_Constituencies__December_2017__UK_BSC_V2-shp) and here for the [river Bann](https://github.com/williammollers/finalproject-ironhack-NI/tree/main/ALL_DATA_SOURCES/ORIGINAL/riversegmentshp1)

##### Presentation

* The final part of this project was a [power point presentation](https://github.com/williammollers/finalproject-ironhack-NI/blob/main/PRESENTATION/Northern%20Ireland%20Presentation.pptx).


There were many challenges in the project, including the following:

First time doing something like this. Therefore I spent a lot of time on structure and hope that the project is easy to read.
Tableau was something that we had barely touched before this. Therefore were some visualisations far from ideal, but I am sure this will improve by the next commit.
The project occurred during the 3rd week of Germany's second lockdown. This made exchanging opinion with colleagues very difficult and it was truly an individal project.
Needs of this project
data exploration/descriptive statistics
data processing/cleaning
statistical modeling
writeup/reporting
Getting Started
Clone this repo (for help see this tutorial).
Raw Data is being kept [here]https://github.com/williammollers/housing-regression-ironhack-midtermproject-nov-2020/tree/master/PYTHON_REGRESSION_ANALYSIS) within this repo.
Data processing/transformation scripts are being kept here
Featured Notebooks/Analysis/Deliverables
All in all we had to deliver a MySql query book, a jupyter notebook, a Tableau dashboard, this readme file and a presentation (to be added)

Contact
Feel free to get in touch with me as you wish!
hi@williammollers.com
https://www.linkedin.com/in/williammollers/
