# Tweet-and-Score-Data

The data sets in this repository come from a seven week educational data science course. You have access to data from two iterations of this course, one in 2014 and one in 2015. The course content is disaggregated, EG - Students choose the order in which they wish to tackle each unit. You may be familiar with this format ;) Students complete one unit each week for six weeks, in the seventh week all students must sit the same final exam.

## Scores.csv

This data set contains the unit choices, time spent on each unit in minutes and scores for each unit students recieved. It also contains final exam scores. All scores are represented at a proportion of the overall possible score (0 - 1).

## tweets.csv

Permission was recieved from the students in this course to collect their tweets during the course. This data set contains those tweets, the week in which they were tweeted and if the tweet was a reply to another student in the class.**

** These are real Tweets from the wild, collected by the [Sentiment140](http://help.sentiment140.com/home) team at Stanford. I have attempted to clean them of anything offensive but may have missed something so be aware if you plan on reading the text.

## Project Description

The intervention aims to help teachers know about students' emotion status through tweets and their social network, as well as their learning performances, so that teachers know how to adjust their instructions to improve students' learning engagement and performances in class. 

Intervention rationale: NLP, Social Networked Analysis, Loop Closing
Visualization: Wordcloud, sentiment analysis in ggplot, SNA graph, correlation plot
Explanation:
* Wordcloud and sentiment analysis reflect how students react to the courses they were taking.
* SNA graph generates and analyzes the measures of centrality and betweeness of a class.
* Corrplot shows significant relationship between tweets sentiment and students' learning performances.
* An euto-email is sent to students whose average unit score is below 0.6.

Supported references:
(https://content.sciendo.com/view/journals/eurodl/18/2/article-p74.xml)

