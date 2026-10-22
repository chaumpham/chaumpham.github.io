---
layout: post
title: "The Clock and the Wall: What 59,000 NYC Marathon Finishers Reveal About Pacing"
description: An analysis of every finisher's 5K splits from the 2025 TCS New York City Marathon
date: 2026-10-21 09:00:00 -0500
tags: [dataanalysis]     # TAG names should always be lowercase
---

Every marathon runner gets the same advice: don't go out too fast. I wanted to see how many people actually follow it, and what happens to the ones who don't. So I collected the official results and split times for the 2025 NYC Marathon and looked at how 59,103 finishers paced their 26.2 miles.

The short version: all runners chase the clock, and most of them hit the wall anyway, first on the bridges and hardest on Fifth Avenue. The few who pace evenly spend the second half passing everyone else.

---

## Who ran

In 2025, **31,855 men, 27,110 women and 138 nonbinary runners** finished the race (I excluded 19 runners listed as anonymous). The median man finished in **4:10:19** and the median woman in **4:39:30**.

![Finish time distribution for men and women](/assets/img/nyc_marathon_2025/01_finish_distribution.png)

Look at the spike just before 4:00. For both men and women, the five minutes leading up to the four-hour mark are the tallest bar on the chart, and the bar right after drops off sharply. Breaking four hours is the classic goal for fit recreational runners, so it’s nice to see the data confirm what every runner already knows.

## 1. Runners sprint to beat the clock

When I counted finishers minute by minute, the pattern got sharper. **602 runners finished at 3:58 and 580 at 3:59, but only 395 at 4:00.** In the five minutes before four hours, 2,674 people crossed the line, compared with 1,910 in the five minutes after: **1.4 times as many**.

![Finishers per minute, with the five minutes before each round-number goal highlighted](/assets/img/nyc_marathon_2025/02_round_number_barriers.png)

The same pattern shows up at every major goal time:

| Goal | 5 min before | 5 min after | Ratio |
|---|---:|---:|---:|
| 3:00 | 769 | 625 | **1.23** |
| 3:30 | 1,530 | 1,462 | 1.05 |
| 4:00 | 2,674 | 1,910 | **1.40** |
| 4:30 | 2,018 | 1,827 | 1.10 |
| 5:00 | 1,709 | 1,339 | **1.28** |
| 5:30 | 1,024 | 897 | 1.14 |

To check this isn't just random noise, I ran the same comparison at times nobody aims for (3:10, 3:40, 4:10, 4:40, 5:10). Those ratios all fall between **0.92 and 1.06**. The bunching only happens at round numbers, and it's strongest at the "big" ones: 3, 4 and 5 hours.

Anyone who’s run a marathon knows the feeling: you check your watch late in the race, see a goal time still within reach, and find a way to dig deeper. The data shows thousands of people doing exactly that.

## 2. Almost everyone slows down, and slower runners slow down more

The classic advice is to run an *even* or *negative* split, meaning the second half as fast as or faster than the first. Very few people manage it. Only **7.5% of finishers** ran a negative split. The median runner's second half was **10.5% slower** than their first.

![Median second-half slowdown by finish time and gender](/assets/img/nyc_marathon_2025/03_second_half_slowdown.png)

Two patterns stand out:

- **Slowdown grows with finish time.** Sub-3-hour men slowed by a median of 4%. Men finishing in 5 to 6 hours slowed by 20%, which is about 30 minutes lost in the second half alone.
- **Women pace more evenly than men at every level below elite.** In the 4-5 hour band, the median man slowed 15% while the median woman slowed 9%, and women were twice as likely to run a negative split (9.0% vs 4.4%). This matches research on other big marathons, which suggests men are more likely to start at a pace they can't sustain.

At the very top, all ten elite men ran negative splits; the median elite man was about 1% *faster* in the second half. That's what racing tactics look like when everyone saves something for the end.

## 3. The course decides where it hurts

Second-half slowdown tells you *how much* runners fade, but not *where*. Using the 5K checkpoint splits, I compared each group's pace in every 5K segment with its pace over the first 15K.

![Pace by 5K segment relative to the first 15K, with the course elevation profile below](/assets/img/nyc_marathon_2025/04_segment_fade_with_elevation.png)

For the first 15K, every group holds its pace. Then the lines separate:

- **20-25K:** the first real jump. This stretch includes the Pulaski Bridge at the halfway mark and the long climb onto the **Queensboro Bridge**. The slowest group (6h+) is already running 21% slower than in their first 15K.
- **25-30K:** a brief recovery. Coming down off the bridge onto First Avenue, with its famous wall of noise, most groups speed up slightly, and the 4-5 hour group at least stops slowing down.
- **30-40K:** the wall. Through the Bronx and back into Manhattan, then up the gradual climb of **Fifth Avenue** toward Central Park, pace falls off for every group. Runners in the 4-5 hour band are 18-19% slower here than at the start, and even sub-3-hour runners are about 8% slower.
- **40K to finish:** everyone speeds up again for the last 2.2K. The finish line pulls people in.

The biggest climbs on the course are the bridges, and they line up with the biggest jumps in pace. NYC is a fast course on paper, but its hills are placed exactly where tired legs feel them most.

The timing also depends on the runner. **65% of sub-3-hour runners never had a 5K segment more than 10% slower than their opening pace.** In the 6h+ group, only 4% avoided it, and over half were already 10% slower by 15-20K.

## 4. Even pacing pays off, in places

Does any of this matter if you aren't racing for a time? One way to measure it is overall position. For every finisher, I compared their rank at halfway with their rank at the finish.

![Median places gained from halfway to the finish, by pacing group and finish time](/assets/img/nyc_marathon_2025/05_places_gained.png)

In every finish band, the pattern is the same: **the more evenly you paced, the more people you passed.**

- In the 4-5 hour band, runners who negative-split passed a median of **7,788 people** in the second half.
- Runners in the same band who slowed by 20% or more were passed by a median of **6,610**.

That's a swing of more than 14,000 places between two runners who might have crossed halfway side by side.

To be fair, part of this is built in: if you slow down more than the people around you, you lose places almost by definition. The interesting part is the size of the effect, and how few people are on the winning side of it. In the 4-5 hour band, 5,138 runners slowed by 20% or more, while only 1,478 ran a negative split.

## What I take away from this

1. **A goal time is worth chasing.** When a goal is within reach late in the race, most of us have more left than we think. That spike at 4:00 shows how much the goal means to runners.
2. **The race really starts at 20K.** The first 15K feels easy for almost everyone. The bridges between 20K and 25K and the Fifth Avenue climb in the last few miles are where your race is decided, so run the first half like you’ll need something left for them.
3. **Even pacing is rare, and that’s why it pays.** Only about 1 in 13 finishers ran a negative split, and they spent the second half passing thousands of people.

---

## How I did this

- **Data:** official 2025 NYC Marathon results and 5K checkpoint splits for every finisher, collected from the public results site. 58,664 runners had both halfway and finish times; 19 anonymous entries were excluded.
- **Tools:** I built the analysis in SQL (DuckDB) in Hex and then ported it to Python (pandas and matplotlib) so it's reproducible from a single script.
- **Definitions:**
  - *Finish time* is chip time from start mat to finish.
  - *Second-half slowdown* = (second-half time − first-half time) ÷ first-half time.
  - *Elite* = top 10 men and top 10 women.
  - *Places gained* compares overall rank (men and women combined) at the half-marathon mat and at the finish.
- **Elevation:** the course profile was digitized by hand from a published elevation chart and is accurate to about ±2 m.
