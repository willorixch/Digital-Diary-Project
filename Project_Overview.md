# Digitial Dirary Project Breakdwon

## Overview
- This project involved processing and analyzing 60 participants’ weekly digital diary submissions from the Snap Academies program over a 9-week period. Each participant provided a new diary entry every week, resulting in 540 total journal segments tied to a single program cycle.
- The entries reflect how participants navigated their learning journey, the progression of their skills, challenges they faced, and how they managed their personal and professional balance throughout the program. The diary entries also identify each individual as part of one of four cohorts: Design, Engineering, Lens, and Storytelling.

- The main challenge was transforming a qualitative dataset, i.e personal and written reflections into structured numerical insights that could be visualized and evaluated. To accomplish this, I conducted a two-phase analysis pipeline: 
  - First, I completed a qualitative review of the diary content to tag participant themes and construct persona archetypes that represent resilience, confidence growth, and sustained motivation. The personas currently mapped include category clusters such as “Blossoming Grinder,” “Confidence Catalyst,” “Global Mover,” and “Resilience Builder.”
  - Second, after structuring the raw reflections, I transitioned into quantitative analysis using pandas, converting the qualitative persona tags into count-based metrics grouped across cohorts. This enabled sentiment-style cohort comparisons, aggregated persona breakdowns, a correlation heatmap to explore relationships across categories, and a 2×2 chart suite to view cohort totals per persona.

## Categorical Description
- Sentiment: Captures the emotional tone of a participant’s reflection, classified as positive, negative, or neutral. This metric reveals overall morale and attitude shifts across weeks.
- Future Anticipation: Tracks how participants feel about what’s next, whether they express hope, uncertainty, or excitement toward the future. Helps gauge confidence in outcomes and forward outlook.
- Stress Management: Measures how participants handle pressure, including coping strategies, time-management struggles, or emotional overwhelm. Provides insight into adaptability and emotional regulation.
- Work-Life Balance: Identifies how participants describe the split between responsibilities and personal well-being. This includes whether both are heavy, balanced, or not mentioned.
- Progress: Flags reflections that mention personal or professional wins, skill improvement, or momentum gained. Shows who felt improvement and when they felt it.
- Obstacles: Highlights challenges such as confusion in coursework, lack of resources, burnout, or competing responsibilities. This category contextualizes dips or stagnation in progress.
- Learning: Tracks concrete insights about skills gained, topics mastered, or new concepts understood. This is a key indicator of technical and soft-skill acquisition across cohorts.

## Persona Breakdown

##### This project processed 60 participants’ weekly reflections from the 9-week Snap Academies program, which organizes learners into distinct cohorts. To transform written diaries into measurable insights, I grouped participants by week and cohort, then structured those tallies into a reshaped table that preserved identity indexing. Using those aggregates, I identified dominant behavioral patterns among participants and distilled them into four meaningful personas:

- Blossoming Grinder: Participants who showed steady engagement from start to finish. Their weekly entries reflect consistency, persistence, and continuous progress, meaning they sustained effort across all 9 weeks without dramatic drop-offs. Their growth is not one breakthrough moment, but a long, reliable upward trajectory.

- Confidence Catalyst: Participants who entered the program uncertain or hesitant but developed noticeable self-assurance as weeks progressed. Their responses indicate turning points where confusion shifted into clarity, participation into contribution, and interest into momentum. Their diaries highlight increased comfort, creativity, and willingness to take ownership of tasks over time.

- Resilience Builder: Participants who explicitly discussed overcoming challenges amid academic or personal pressure. Their responses include mentions of setbacks, adaptation, and skill development despite obstacles. These individuals show emotional and technical flexibility, often bouncing back stronger after difficult weeks, aligning with a narrative of persistence through adversity.

- Global Mover: A smaller group of participants (5 total) who traveled or relocated to attend the program, or whose cultural/academic perspectives differ from typical domestic participants. While fewer in number, their diaries add a dimension of mobility, transition, and navigating unfamiliar environments while maintaining academic focus.
