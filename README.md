# Visualizations
## Author: Tyler Ursuy

  This dataset is made up of ten years of English Premier League (PL) soccer seasons hosted in Great Britain. The data 
  includes the date, home team, away team, home team goals, away team goals, the referee for the match, home and away team 
  red and yellow cards, and more. Each row is comparable to a less detailed box score report. I was lucky enough to find a 
  website that had all of this conveniently in one place and downloaded all ten CSVs, one for each season, from datahub.
	
  As someone who has followed the PL for many years, I was very excited to find a dataset that would allow me to learn more 
  about my favorite league. Additionally, I knew that I would be able to tease out plenty of insights by asking the right 
  questions since I have some level domain expertise. The PL also happens to be the home of my favorite team, Manchester 
  United, and the opportunity to be a data driven fan was hard to pass up on.
  
  The dataset provided a great foundation to start but was lacking in some areas. Firstly, the locations of each team were 
  not listed; however, I was able to manually add this by matching each to team to its corresponding subnational territory 
  listed in the Nomenclature of Territorial Units for Statistics, commonly referred to as NUTS Europe. For the purposes of 
  one particular visualization below, I gathered the coordinates of London team stadiums. Next, as I will expand on later, 
  I added the number of times each team has won the PL. The last piece of additional information I had to find was the rival 
  of each team. Each of these was done by internet searches and manually recorded. Any additional information used other 
  than the ones just listed was done by feature engineering using the data available.
  
  While beginning the project, I had a few initial questions that I wanted answers for, but my curiosity grew with each 
  type of visualization. One of my first questions aimed to find out what teams would be leading if I treated all ten years
  as one season, that is, keeping track of a cumulative point count for ten years rather than resetting each year. I then 
  wanted to investigate the impact of referees on games by observing how many yellow and red cards each referee issued. 
  Next, I was curious to see if teams played differently when they were home against being away. These are only a few 
  initial questions, but I will elaborate on these and many more with this report.
  
  Please see the notebooks and Tableau workbooks for code and the attached report for a explanations of each.
