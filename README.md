# HCI2001-COIN-Project
This Github repository contains all supplementary files used in our COIN project
for the course, Computational Interaction Design, at DLSU - Manila. This study is
titled **Evaluating and Redesigning the Canvas LMS Dashboard**. We created three
new dashboard views: a redesigned list, redesigned card, and carousel. Through
user testing, we discovered that there are significant differences in the 
completion time and target accuracy when users complete certain tasks across 
each dashboard view. This suggests that the layout of Canvas' dashboard affects 
the speed and accuracy at which users are able to identify the page they wish to
open.

After analyzing our results, we were able to gather the much needed insights to 
prove that the current layout of the Canvas LMS dashboard falls flat in several aspects. 
It has been observed that for each performance metric measured: (a) task completion
time and (b) target identification accuracy, and for each task completed: (a) clicking
on a certain urgent task and (b) clicking on a certain unread announcement, the 
redesigned views have shown better results.

# Prototype
The prototype folder contains our recreation of Canvas' two default views, and our
three redesigned layous, implemented using HTML and CSS. 
- `start.html`: HTML file used for user testing. Contains all views and tasks, and automatically measures the performance metric for each.
- `cardView.css` and `cardView.html`: Redesigned card view
- `carouselView.css` and `carouselView.html`: Redesigned carousel view
- `listView.css` and `listView.html`: Redesigned list view
- `defCard.css` and `DefaultCard.html`: Default card view
- `defList.css` and `DefaultList.html`: Default list view
- `images`: Folder containing all images used during the creation of each dashboard view

# Statistical Analysis
We used a Jupyter notebook to clean and analyze our test results. We utilized
various libraries such as pandas, scipy and statsmodels to create boxplots, perform
one-way ANOVA and Tukey's Test. By doing so, we were able to derive insights from our initial findings.
- `statAnalysis.ipynb`: Jupyter notebook used for cleaning and data analysis

The folder also contains the datasets (user test results) we used for analysis.
<br>
**Uncleaned datasets**
- `data1.csv`: Completion Time for Task #1 (clicking on a certain urgent task)
- `data2.csv`: Completion Time for Task #2 (clicking on a certain unread announcement)
- `data3.csv`: Target Identification Accuracy for Task #1 (clicking on a certain urgent task)
- `data4.csv`: Target Identification Accuracy for Task #2 (clicking on a certain unread announcement)
<br>
**Cleaned datasets**
- `cleaned-data1.csv`: Completion Time for Task #1 (clicking on a certain urgent task)
- `cleaned-data2.csv`: Completion Time for Task #2 (clicking on a certain unread announcement)
- `cleaned-data3.csv`: Target Identification Accuracy for Task #1 (clicking on a certain urgent task)
- `cleaned-data4.csv`: Target Identification Accuracy for Task #2 (clicking on a certain unread announcement)




