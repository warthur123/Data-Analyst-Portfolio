# Data Portfolio

This portfolio consolidates major data-related projects I have completed, with a majority of projects coming from undergraduate Information Science course projects at the University of Maryland, College Park. 

This portfolio highlights the breadth of knowledge and skills for data learned, ranging from database queries and schemas to topic analysis in Python. It also reveals the depth of my knowledge of coding in Python, utilizing many different data libraries to perform a variety of analysis.

## Content

- ### AZ Song Lyrics Analysis ### 
    - Lyrics analysis on songs scraped from AZLyrics.com. 
    - Scraped song data and lyric urls for all songs with artist names starting with the letter 'W' using Python BeautifulSoup. Then obtained smaller sample data of song lyrics.
    - Cleaned and preprocessed sample data, removing stopwords and stem words. Then analyzed total words, unique words and ratio betwen total and unique, as a function of year, and performed simple linear regression on unique and total word ratio and year. 

    **_Tools: Python (Pandas, BeautifulSoup, NumPy, NLTK, SKLearn, PyPlot), Jupyter Notebook_**


- ### Billboard Top 100 Database ###
    - Developed and populated a Database Schema for all Billboard Hot 100 songs from 1964 to 2020.
    - Drew and combined data from two datasets from Kaggle and data.world by users rakannimer and kcmillersean.
    - Developed 5 advanced queries and ERD to supplement database.

    **_Tools: MySQL, MySQL Workbench_**


- ### Business Case Study ###
    - Sample business case study to practice LP models and making predictions through analyzing variables.
    - Developed an LP model to determine how much money they should invest in various employee focused departments, and performed a regression model to examine relationship between tenure and hypothesized variables. 

    **_Tools: MS Excel, R_**
    
    
- ### DC Water Impervious Area Consulting Capstone Project ###
    - Created two new enriched impervious area tables for 2013 and 2019 data by joining DC Open Data datasets with data from DC Water’s internal ArcMap databases.
    - Generated and delivered a final Power BI dashboard comparing 2013 and 2019 data, supplemented with a dashboard manual and a future actions report.

    **_Tools: Power BI, MySQL, ArcMap/ArcGIS, Citrix_**


- ### PG County Vaccine Availability Alert ###
    - Developed a python script using Selenium that scans website for open appointment slots for COVID-19 vaccines. 
    - Developed for client in the UMD HCIL department.

    **_Tools: Python (Selenium)_**


- ### Video Game Rating Analysis ###
  Developed 4 data reports on video game sales and popularity dataset from Kaggle by user Kirubi. All analysis were performed in R.
    - **Report 1:** Performed a multi-variate analysis to determine correlation between video game platform and critic score, and frequency of video games per genre by platform.
    - **Report 2:** Analyzed if critic score varied based on platform (Xbox 360. Wii, PS3) by performing a multi-variate analysis using Chi Square Test of Independence, Effict Size and Power, and determined effect size through Cramer's V test.
    - **Report 3:** Performed a two-way ANOVA test to examine relationship between platform, genre and critic score, analyzed the pairwise differences between each grouping of main effects in the model using TukeyHSD, and determined the effect size through Cohen's F, R-squared analysis and partial eta-squared analysis.
    - **Report 4:** Determined the association between game sales in North America and critic score, user score, platform and genre using linear and multiple regressions modeling.


    **_Tools: R (tidyverse, ggplot2, knitr, descr, stargazer, sjPlot, webshot, DescTools), RStudio_**


- ### Facebook COVID News Analysis ###
    - Data analysis and report on how different major news organizations cover COVID-19 on Facebook and how they differ in public engagement.
    - Fetched data from Facebook using [Facepager](https://github.com/strohne/Facepager) and cleaned data in Python.
    - Performed public engagement analysis through bargraph visualizations and comparing average number of emoji reactions, shares and comments between different news organizations.
    - Performed Topic Analysis using Gensim's LDA models and pyLDAvis models to determine top key words used by each major news organization.
    - Performed Time Series Analysis using Pandas to determine how number of posts by news organizations has changed each quarter.

    **_Tools: Python (Pandas, NumPy, NLTK, SKLearn, gensim, pyLDAvis, spacy, ), Jupyter Notebook_**
