# Project - Data Scientist Salarys in USA

## Description
The process of getting a job is pretty hard, starting from the interviews and going all the way to the salary negotiation.

This project aims to help Data Scientists in this last step, giving them an estimate salary based on some infos about the job/company.

## Overview
* Scrapped almost 1700 jobs data from glassdoor using python.
* Explored the data trying to find some non-obvious correlations 
    * Engineered features from job description to quantify dependency of some requirements (python, sql, aws, spark, hadoop, phd, etc).
* Created a model with a 16K mean absolute error on predicting a job salary (yearly).

## Project Timeline


### Web Scrapping

Did some modification on an pre-existing scrapper code (credits below) to scrap about 1700 jobs postings from Glassdoor. 

Those were keeped in two parts, with ~850 jobs each. That's beacause the site has a maximum of 30 pgs per research and each time a different job may appear. With each job we tried to get the following:

* Job Title
* Salary Estimate
* Job Description
* Rating
* Company Name
* Location
* Headquarters (no data found, may be due to my location)
* Size
* Founded
* Type of ownership
* Industry
* Sector
* Revenue
* Competitors (no data found, may be due to my location)


### Data Cleaning




## Credits
The glassdoor scrapper main code idea was taken from [this](https://github.com/arapfaik/scraping-glassdoor-selenium) GitHub repo.
* Some minor changes were made to fix some bugs