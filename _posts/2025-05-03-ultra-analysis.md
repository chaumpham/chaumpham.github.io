---
layout: post 
title: Ultramarathon Analysis
tags: [dataanalysis]     # TAG names should always be lowercase
---
On March 29, 2025, I ran my first ultramarathon, a 50K race along Chicago’s scenic lakefront trail. It was my first time running further than the marathon distance, and my goal was simply to finish. The final 10 miles were especially tough, but I made it to the finish line!

Since I love digging into data, I naturally downloaded the official race results and registration data to explore who ran the race and how we all performed. _I conducted the analysis in Python, using pandas, seaborn, and matplotlib. If you’re curious to see the code or run the notebook yourself, you can check it out on my [GitHub](https://github.com/chaumpham)._

This blog shares some of the insights I uncovered.

## ⚡ Key Takeaways (TLDR Version)

**1. Age isn’t a limitation, it’s an asset:** Some of the most consistent and fastest finish times came from runners in their 30s, 40s, and even 50s. Men, in particular, showed remarkable consistency, with average finish times staying within a 30-minute range across ages 18 to 59.
**2. Women hold their ground in ultras:** Despite making up just a third of participants, women had a slightly higher completion rate and performed competitively across age groups. While small sample sizes limit broad conclusions, the data suggests women are more than capable of keeping pace with their male counterparts.
**3. Variability reveals the deeper story:** Looking beyond averages to examine variance, skewness, and distribution helps uncover the real dynamics of the race, highlighting everything from experience gaps and participation trends.

## 🤔 Questions I Asked Before Looking at the Data

As a runner, I had a few hypotheses going into this analysis:

**1. How many people finished the race?**

I expected a high finisher rate. Ultra running tends to attract highly motivated athletes who train seriously, unlike marathons, which can attract more casual participants checking off a bucket-list goal.

**2. Are there performance differences between male and female runners?**

I assumed men would be faster overall, due to biological factors and the fact that ultra running is still a male-dominated sport. 

**3. Does age impact performance?**
My hunch was that older runners might outperform younger ones. Anecdotally, I was passed by many seasoned runners during the race. It was humbling and very motivating! 😅

## 📊 Who Showed Up and Finished?

![Chart 1](/assets/img/ultra_analysis/race-registrants-bar-chart.png)
![Chart 1](/assets/img/ultra_analysis/race-finishers-bar-chart.png)
