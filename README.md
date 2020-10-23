![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Business Intelligence with Tableau: Hearthstone Qualifiers to Madrid, a Results analysis

## Overview

This project tries to show in a clear and explainatory way all the results found in previous project, like data extraction and statistical analysis and show them in a direct and explainatory fashion. 

---

[Link to the presentation in Tableau public](https://public.tableau.com/profile/alexander.gimenez#!/vizhome/HearthstoneMastersQualifiersResultsAnalysis/HearthstoneMadridQualifiersAtournamentresultsanalysis)

## Steps I followed to perform this project

### 1- Getting your data
I decided to use the same data that I used before for previous projects since I was familiar with the dataset. 

### 2- Analyzing the shape of your data

I realized that the way my data was structured didn't allow me to many of the graphic representations I wanted to use, so I had to reshape some of the data using melt functions
and then merging the results together. 

### 3- Importing data into Tableau 

Once I imported the data into Tableau I had to change to comma separated values the CSV and set the language to English so it could parse correctly the dates.

### 4- Creating the graphs

For the graphs I knew I wanted to tell the story on how popularity and winrate trends affect Hearthstone tournaments, as well as new deck discoveries and improvements over time so I started creating a summary of the decks most played grouping by class.
Then I though it's not only important to see which were the most played classes but to analyze the trends. So 2 new graphs included to see how the played rate of each class got affected across time.

Then I tacleked the winrate graphs, which sadly I couldn't find another suitable graph representation to do them. 

I adjusted the linear regressions of the graphs to be polynomic so the curve adjusted better to the data.

After this I realized first of all I wanted to do some summary statistics in a simple chart visualization and a calendar form to show how the tournaments were distributed over time.

### 5- Creating the story and adding comments

I generated a new story and added some comments to explain better some of the observation of the graphs included. 

### 6- Possible improvements&Lessons learnt

Maybe data could be structured in some other way so I could had use another form of graphs to make it less monotone. 

I should have collected more data on players so I could show & calculate how many players calculated using the 4 top 16º rule.

Should study more tableau to see more automations and cool features to make the dashboards more look more dynamic.

The data should have more ways to filter and analyze in more dimensions.
