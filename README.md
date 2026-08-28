# Bellabeat Wellness Case Study

## Project Overview

This case study analyzes Fitbit smart-device usage data to identify patterns in physical activity, sedentary behavior, and daily activity consistency and translate those findings into recommendations for Bellabeat’s marketing strategy.

The analysis examines activity patterns across 35 users and identifies differences between lower- and higher-activity users, with a focus on sedentary behavior, consistency, very-low-activity days, and periods of sustained activity.

## Business Objective

The objective of this analysis is to identify trends in smart-device usage and determine how these insights could inform Bellabeat’s marketing strategy.

### Key Business Questions

* What trends can be identified in smart-device usage and physical activity?
* How do these trends reveal differences in user behavior?
* How could these insights inform Bellabeat’s marketing strategy?

## Key Findings

* **Activity levels varied substantially:** Average daily steps ranged from 774 to 16,759, with 11 of 35 users averaging fewer than 5,000 steps per day.
* **Lower-activity users were more sedentary:** Lower-activity users spent an average of 81.3% of the day sedentary, compared with 65.2% among higher-activity users.
* **Higher-activity users were more consistent:** The average coefficient of variation in daily steps was 46.5% among higher-activity users compared with 115.1% among lower-activity users.
* **Very-low-activity days were more common among lower-activity users:** 47.8% of recorded days among lower-activity users were below 2,000 steps, compared with 7.4% among higher-activity users.
* **Afternoon activity was a potential engagement opportunity:** 22 of 34 users demonstrated their highest sustained activity during the afternoon.

## Recommendations

Based on the findings, the analysis recommends that Bellabeat:

1. Reduce prolonged sedentary behavior through personalized movement reminders.
2. Address very-low-activity days with achievable minimum-movement goals.
3. Encourage consistency through personalized weekly activity goals.
4. Strategically time engagement around observed afternoon activity patterns.

## Tools & Technologies

* **Python / pandas** — Initial data inventory and assessment
* **Google Sheets** — Data cleaning, validation, aggregation, and analysis
* **SQL / BigQuery** — Data analysis and user-level segmentation
* **Tableau** — Data visualization and dashboard development

## Data

The analysis uses the Fitbit Fitness Tracker Data dataset available through Mobius on Kaggle. The dataset contains activity and wellness observations collected from 35 users across two collection periods between March 12 and May 12, 2016.

## Limitations

The dataset is relatively small and does not provide sufficient demographic or contextual information to determine whether observed activity differences are associated with factors such as age, occupation, or other individual characteristics. Sleep data was also available for only 24 of the 35 users.

The findings should therefore be considered directional insights rather than definitive conclusions about Bellabeat's broader customer base.

## Project Deliverables

* Full case study documentation
* Condensed portfolio case study
* Tableau visualizations and dashboard
* Supporting analysis and data-cleaning work

