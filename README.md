# vanguard-ab-test

Vanguard A/B Testing Project
Overview
This project involves analyzing the results of an A/B test conducted to evaluate the impact of a new user interface design on the completion rates of a specific process. The experiment was conducted between March 15, 2017, and June 20, 2017, comparing the existing (Control) design with a new (Test) design.

Files in Repository
df_final_demo.txt: Contains demographic information of clients.
df_final_experiment_clients.txt: Lists clients involved in the experiment.
df_final_web_data_pt_1.txt: Contains web interaction data (part 1).
df_final_web_data_pt_2.txt: Contains web interaction data (part 2).
merged_data.csv: The combined dataset used for analysis.
Analysis
Hypothesis 1: Completion Rate
Null Hypothesis (H₀): The completion rate for the Test group (new design) is equal to the completion rate for the Control group (old design).
Alternative Hypothesis (Hₐ): The completion rate for the Test group (new design) is different from the completion rate for the Control group (old design).

Control Group Completion Rate: 12.20%
Test Group Completion Rate: 14.46%
Statistical Test: Z-Test

Z-statistic: -18.6732
P-value: 8.17e-78
Interpretation: The new design led to a statistically significant increase in the completion rate.

Hypothesis 2: Cost-Effectiveness
Threshold: A 5% increase in completion rate.

Actual Increase: 18.52% (from 12.20% to 14.46%)
Interpretation: The new design exceeded the cost-effectiveness threshold.
Hypothesis 3: Client Demographics (Age, Gender, Tenure)
Age:

T-statistic: nan
P-value: nan
Issue: Data issues caused invalid test results.
Tenure:

T-statistic: nan
P-value: nan
Issue: Data issues caused invalid test results.
Gender:

Chi-square Statistic: 54.2977
P-value: 0.0000
Interpretation: Significant difference in gender distribution between the groups.
Time Spent on Each Step
Average Time Spent (in seconds):

Control Group:

Start: 184.35
Step 1: nan
Step 2: nan
Step 3: nan
Confirm: 128.28
Test Group:

Start: 152.27
Step 1: nan
Step 2: nan
Step 3: nan
Confirm: 126.31
Experiment Evaluation
Design Effectiveness
Well-structured Experiment: The experiment had a defined structure with Control and Test groups.
Random Division: Random assignment is assumed but not explicitly detailed.
Biases: Potential biases exist if the randomization process was flawed or if external factors influenced the results.
Duration Assessment
Adequacy of Timeframe: The experiment period appears reasonable but depends on behavior change timelines, sample size, and seasonal factors.
Additional Data Needs
Demographic Information: More detailed data on age, gender, and income levels.
User Feedback: Qualitative insights from surveys or feedback forms.
Geographical Data: Regional variations in response to the new design.
Session Interaction Patterns: Granular data on session durations and click-through rates.
Conversion Funnel Analysis: Data on conversion rates at each process step.
Competitor Analysis: Industry benchmarks for context.
