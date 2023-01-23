<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Degree </a></h3>
<h4 align="center">  Project V: Communicate Data Findings </h4>
<h5 align="center">  January 2023 </h4>

## Table of Contents
- [Introduction](#Introduction)
- [Project Instruction](#instruction)
- [Project Motivation](#ProjectMotivation)
- [Project Submission](#submission)
- [Result](#result)

## Introduction <a name="Introduction"></a>

In this project, I've selected the  TMDB Movie Data Analysis which contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. The data is cleaned from the <a href = "https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata">kaggle</a> original data and making a question analysis in the following: 

## Udacity's Project Instruction <a name="instruction"></a>
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

In Part I, Exploratory data visualization, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.

In Part II, Explanatory data visualization, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

## Project Motivation <a name="ProjectMotivation"></a>

Data visualization is an important skill that is used in many parts of the data analysis process.
<ul>
<li><strong>Exploratory</strong><br> data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. </li>
<li><strong>Explanatory</strong><br> data visualization techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.</li>
</ul>
 
  


## Project Submission <a name ='submission'></a>
What to include in your submission:
<ul>
  <li><strong>Part_I_exploration_template.ipynb</strong> - This is your starting point for the project Part I. This file contains multiple sections to help you organize your exploration. At the end of each section, there are questions to help you summarize your findings and reflect on the steps taken through the investigation.</li>
<li><strong>Part_II_slide_deck_template.ipynb</strong> - This is your starting point for the project Part II. This file contains starter cells to help you organize your slide-deck deliverable. These cells provide examples of how the slide deck should be organized, including pre-set slideshow settings.</li>
<li><strong>README.md </strong> - This markdown file contains the following sections that you will fill as you progress through the project.</li>
<ul>
        <li> Dataset</li>
        <li> Summary of Findings</li>
        <li> Key Insights for Presentation</li> 
   </ul> 

</ul>

## Result <a name="result"></a>
I've generated three files which are exploration file, slide deck and README.md for this project which you can find the analysis and plan of attack for making a slide deck.


<hr>
Below is the part of README.md submitted for this project

# (Go Bike Data Set)

## by (Tae Singhanart)


## Dataset

I selected Ford GoBike System Data which includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Originally, there were 183,412 entries with 16 features in this dataset. I retreived the dataset from [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

The main feature I'm interested in this data set is user type, customer and subscriber. I want to see some different or commonality (if any) relationship with other features such as the duration of the ride, gender, and age. 

The finding is showing that t the age profile of customer and subscriber group is quite simliar. For the gender by user type, there are more male member in both group. Noticably, the number of male subscriber is far way more than the other group around 3-25 folds. The customer group seem to have longer duration ride than subscriber. In Gender wise, both subscriber and customer group, male gender take a more ride. For both group most ride are take around 1 - 40 minutes. It's also show that the member after 60 year olds who taking the trip from 1-40 minutes are mostly customer than the subscriber. Lastly,  the exploration also showing that in each top three place, the majority group of visitor is different between subscriber and customer. For example, Market St at 10 St, the subscriber with the below 20 and mids 20 are the most group riding to this place while the customer group is the age over 30. In marketing perspective, this information help the company gain a huge advantage when it come to lauching the promotion on site or select target group for some specific promotion.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

For the presentation, I will focus on just user type. I will start by introducing the the user_type variable showing the number of users by type, Next, showing its  and age profile (violin plot) and gender(bar plot).

Afterwards, I will describe the characteristic of the ride duration by user type (bivariable) and ride duration, user_type and age (multivariable). Lastly I will present the difference in number of ride of the top three destination by user type and age (multivariable).
