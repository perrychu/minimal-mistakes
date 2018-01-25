---
title: "First Post"
tags: [Data science, Metis, Blog]
---

##Metis

Last week, my cohort started at Metis, a project-centered data science bootcamp. Over 12 weeks, ~30 of us are learning the full process - data acquisition, cleaning, exploratory analysis, modeling, and presenting.  

Our first project was centered on cleaning and exploratory analysis of MTA turnstile data (http://web.mta.info/developers/turnstile.html). I
This is a blog post about munging the MTA data and what I've learned so far.

##MTA data project - Optimizing food truck routing

###Our project
For our project, we decided to look at optimal routing for a food truck which served crepes for breakfast, lunch, and dinner on weekdays. The question was - which stations should our client's truck park at for each meal period?

To answer the question, we tried to find the average traffic through each station for each meal period:
-Breakfast: ~7am-11am
-Lunch: ~11am-3pm
-Dinner: ~3pm-7pm

Then, we would find the "optimal" routes by assuming a flat conversion rate from traffic to sales and subtracting a penalty for travel time between stations.

###The MTA data
The data is a CSV of cumulative entry and exit counts by turnstile at MTA stations. A value is recorded (roughly) every 4 hours, plus occasional irregular audits. 

Some of the problems we ran into:
-Turnstile counts sometimes reset without warning
-Turnstile counts sometimes didn't record
-Record times sometimes changed (e.g. some days it would record at midnight, 4am, 8am, etc. and others it would record 1am, 5am, 9am, etc.)

To deal with these issues, we loaded the data into pandas. We calculated differences in cumulative values to get to actual entries / exit per time period, and took out outliers.

###The Results
In the end, we found that Grand Central Station has the most traffic throughout the day (breakfast, lunch, and dinner). However, the second best route would be 34th Penn Station (Breakfast) -> 34th Herald Square (Lunch, Dinner) even accounting for travel time.  

That said, the next two routes were 34th Herald all day or 34th Penn all day... so if a business had 3 carts, they would park at Grand Central, 34th Herald, and 34th Penn Station.





