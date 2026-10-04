# T38 Employee Survey Theme Coder

## Student Details

- **Name:** Risha Agarwal
- **Program:** MBA (DS&DA), SCIT Pune
- **PRN No:** 26030242050
- **Task ID:** T38
- **Theme:** Employee survey theme coder
- **Course:** AI Powered Tools mini project

## Project Overview

A company ran an engagement survey with 300 responses. Each response has five questions scored 1 to 5, an eNPS score and one open comment. The aim of this project is to use free AI tools to sort the comments into themes and tone, check how accurate that is, and link the themes to low scores so the HR head knows what to fix first.

## Solution Approach

- ChatGPT (free) suggested six themes: Manager support, Flexibility, Workload, Tools and systems, Pay and benefits, and Career growth.
- I wrote a codebook with meanings, when to use and not use each theme, keywords, and rules for two-theme comments and for tone (Positive or Negative).
- I tested the codebook on 30 comments, then coded all 300 in three batches of 100 and checked for empty cells and wrong theme names.
- I counted themes by tone and department, calculated averages, share of low scores (1 or 2) and eNPS, and compared people with a negative comment on a theme against everyone else.
- Every prompt used the Role, Task, Context, Format, Rules format, and the AI Use Log has 21 entries with four improvement rounds.
- Extra work: an HTML dashboard that shows themes, scores, eNPS and top problems from an uploaded survey file.

## Key Results

- 451 theme mentions in 300 responses (203 Positive, 248 Negative). Overall eNPS is -42.0.
- All 50 rows checked matched the gold labels (100% accuracy). I treat this with care because the rows were the first 50, not a random sample, and the comments repeat a small set of sentences.
- Top three problem themes: **Pay and benefits** (44.7% low scores), **Tools and systems** (36.6% low scores, biggest score gap) and **Workload** (biggest eNPS gap, -52.5).
- The action plan gives each theme an action, an owner, a deadline and a success measure, with the survey to be rerun in April 2027.
- Limits: the data is synthetic, the theme-to-question links are my own choice, and the scores show patterns, not causes.

## Files in this Folder

1. **T38_Employee_survey_theme_coder.xlsx**: main workbook with the 300 responses, gold labels, AI use log, codebook, coded responses, theme counts, Likert summary, theme vs Likert table and the 50 row accuracy check.
2. **T38_Final_Report_with_Action_Plan.docx**: one page action plan for the HR head, then the report (goal, method, accuracy, findings, recommendation, limits, responsible AI notes, reflection).
3. **employee_survey_dashboard.html**: the extra-work dashboard. Upload the survey Excel file and it shows themes, scores, eNPS and top problems.
4. **T38_Dashboard_Input_300.xlsx**: the file to upload in the dashboard, with the survey data and the coded themes and tone for all 300 responses.
5. **Screen recording**: short screen recording (about 1 min 40 sec) showing the workbook and then the dashboard.

## Drive Folder Link

This link has all the screenshots for the evidence asked in the AI log sheet: https://drive.google.com/drive/folders/1FOJGQqnoX1TA6cijtuTd0_0EwIaO9OU9
