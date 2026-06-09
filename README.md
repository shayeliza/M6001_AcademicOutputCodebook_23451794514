# M6001_AcademicOutputCodebook_23451794514
BASc Capstone, London Interdisciplinary School, 2026: Mixed-methods quasi-experiment designing and EVALUATING an urban bird connection toolkit for nature connectedness.

## TL;DR
For the full data analsis, please run Capstone_notebook.ipynb. Necessary libraries and dependencies are embedded in the notebook. To run this file you will need the dataset:
ANONYMISED_dataset.xlsx which contains all data collected across the duration of the study. Identifiers and sensitive information including name, address, and phone numbers have been removed in line with Stage 1 ethical clearance commitments. 
You will also need table_of_measures.png which explains the measures taken - LCN and PTPS. 

## Information about the dataset
ANONYMISED_dataset.xlsx uses shorthand column names, which mean the following: 

### Participant Info
- `ID` — participant code (e.g. P26)
- `Group` - A = intervention (received toolkit immediately), B = waitlist control
- `matched_pair` — pair number assigned at baseline matching (note that matched pairs code has not been included because of unavoidable sensitive information)
- `Status of participation` — completion status (only 'complete' rows are retained for analysis)
- `Task_engagement` — total number of tasks completed out of 10

### Love and Care for Nature Scale (LCN)
In the following, participants were asked: "On the line before each of the following statements, use the scale below to indicate how you generally feel about each one. Be as honest as you can. There are no right or wrong answers."

- `Pre_LCN_1` — baseline score: "I feel a deep love for nature" 
- `Pre_LCN_2` — baseline score: "Protecting the well-being of nature is important to me" 
- `Pre_LCN_3` — baseline score: "I often feel a sense of awe and wonder in nature" 
- `Pre_LCN_4` — baseline score: "I often feel a strong sense of care toward the natural environment" 
- `Pre_LCN_5` — baseline score: "I often feel emotionally close to nature"

- `Post_LCN_1` to `Post_LCN_5` — same items measured post-intervention
  
- `Pre_LCN_score` — mean of all 5 baseline LCN items
- `Post_LCN_score` — mean of all 5 post-intervention LCN items

### Perceived Time Poverty Scale (PTPS)
In the following, participants were asked to: "Please rate the degree to which you agree or disagree with the following statements (1 = strongly disagree,7=strongly agree)"

- `PTPS_1` — "I often feel like there's no time for socialising"
- `PTPS_2` — "I often feel like there's no time for personal recreation"
- `PTPS_3` — "I often feel like there's no time for travelling"
- `PTPS_4` — "I often feel like there's no time for exercising"
- `PTPS_5` — "I often feel like there's no time to do the things that I love to do"
- `PTPS_6` — "I often feel like I don't have time to get things done that I planned in my private life"

- `PTPS_Score` — mean of all 6 items (1–7 scale, higher = more time poor)
- `PTPS_Score` — mean of all 6 PTPS items
