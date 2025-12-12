## Introduction to Analysis

Below is the overall project analysis section. The linked HTML file contains the full end-to-end data pipeline, including all transformation steps, category tagging, association measures, and visual outputs.

## Data Preview (After Cleaning)

The table below shows the key cleaned columns from the digital diary dataset after restructuring. Only standardized and verifiable information is displayed here for clarity. 
The full report and all original columns can be viewed by opening the HTML file linked at the top.

| Participant | Sentiment | Future Anticipation | Stress Management | Work/Life Balance | Progress | Obstacles | Learning | Week   | Cohort |
|------------|-----------|-------------------|------------------|------------------|----------|-----------|----------|--------|--------|
| 2515_SSA   | +         | hopeful           | no mention       | no mention       | no mention | time management, personal | no mention | Week 1 | Storytelling |
| 2515_SLA   | +         | hopeful           | no mention       | no mention       | no mention | personal, professional | no mention | Week 1 | Lens |
| 2515_SEA   | +         | hopeful           | no mention       | no mention       | no mention | personal, professional | no mention | Week 1 | Engineering |
| 2515_SDA   | +         | hopeful           | no mention       | no mention       | no mention | personal | no mention | Week 1 | Design |
| 2514_SSA   | +         | hopeful           | no mention       | no mention       | personal growth | personal, professional | no mention | Week 1 | Storytelling |


## General Visualizations

### Cramér’s V Confusion Matrix
A confusion matrix compares two categorical columns by counting how often each pair of labels occurs together, forming the basis for the chi-square test. In this project, it helps quantify relationships like how a participant’s weekly sentiment aligns with stress, anticipation, or learning patterns.

<img width="754" height="656" alt="image" src="https://github.com/user-attachments/assets/0c9b44d6-32e8-4698-851b-35d0f84ce130" />


### Insights from Cramér’s V Heatmap
Cramér’s V values range from 0 to 1, where higher values suggest stronger categorical association. The strongest measured relationship in the full analysis was between **Sentiment and Future Anticipation (0.51)**, followed by **Stress Management and Sentiment (0.48)**, showing that emotional tone often aligns with stress handling and future outlook.


### Interpretation Summary
Weekly feelings influence future outlook and stress levels. Positive or negative weeks shape both current emotional strain and expectations for upcoming weeks.


### Stacked Bar Chart: Sentiment by Week & Cohort


<img width="1097" height="797" alt="image" src="https://github.com/user-attachments/assets/bf86ec4a-3e71-478c-9308-fb56b70ac7a8" />


### Stacked Bar Chart: Future Anticipation by Week & Cohort


<img width="1097" height="797" alt="image" src="https://github.com/user-attachments/assets/15364f7e-93b1-4938-a3f5-8bf74d01b3ec" />


### Stacked Bar Chart: Work/Life Balance by Week & Cohort


<img width="1097" height="797" alt="image" src="https://github.com/user-attachments/assets/a620e108-7d49-49a5-bcc0-4674dbaa8651" />


## Personas Visualization 
This section will categorize participants into personas based on emotional and technical development signals reflected in weekly diary themes.

## Data Preview (After Adding Persona Coloumn)

| Participant | Sentiment | Future Anticipation | Stress Management | Work/Life Balance | Progress | Obstacles | Learning | Week | Cohort | Persona |
|------------|-----------|-------------------|------------------|------------------|----------|-----------|----------|--------|--------|--------|
| 2515_SSA   | +         | hopeful           | no mention       | no mention       | no mention | time management, personal | no mention | Week 1 | Storytelling | Blossoming Grinder |
| 2515_SLA   | +         | hopeful           | no mention       | no mention       | no mention | personal, professional | no mention | Week 1 | Lens | Confidence Catalyst |
| 2515_SEA   | +         | hopeful           | no mention       | no mention       | no mention | personal, professional | no mention | Week 1 | Engineering | Blossoming Grinder |
| 2515_SDA   | +         | hopeful           | no mention       | no mention       | no mention | personal | no mention | Week 1 | Design | Resilience Builder |
| 2514_SSA   | +         | hopeful           | no mention       | no mention       | "personal (communication, confidence, organization..)" | personal | no mention | Week 1 | Storytelling | Confidence Catalyst |


## Persona Distribution (Overall)

This pie chart visualizes the overall semantic distribution of participant personas after diary analysis was restructured for week-level tracking. 

<img width="614" height="432" alt="image" src="https://github.com/user-attachments/assets/fe3bb47d-beb0-4331-b4d4-91d25f0ce45c" />

## Persona by Cohort (Bar Chart Breakdown)

These bar charts segment persona patterns for each cohort track independently, displayed as four separate charts for clear comparison of persona frequency across Storytelling, Lens, Engineering, and Design participant groups.

<img width="784" height="614" alt="image" src="https://github.com/user-attachments/assets/76155a45-6940-4326-a940-c3203e7931c7" />


