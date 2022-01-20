Challenge: HR Analytics - Job Change of Data Scientists

Purpose: Enable HR department of  to predict the probability of candidates who will move to a new job, with goal of reducing the cost and time as well as the quality of training or planning

TechStack: 
  -Cleaning, Wrangling, Interacting with data: Pandas, NumPy | 
  -Visualization: Matplotlib, Plotly

Data Sources: Kaggle API

Acceptance criteria: 
-Employer is able to predict probability of candidate to remain with company
-Employer is able to determine/pinpoint the factors which influence candidate's decision (demographics, education, experience)

In case of imbalanced data pulled from API, such as an unequal number of samples for each  demographic class (specifically for the minority class, due to biases which may be introduced during data collection), I will implement Synthetic Minority Over-sampling Technique in Python, or alternately:
  1. Sampling with replacement- add copies of instances from the under-represented class called over-sampling 
  2. Under-sampling- delete instances from the over-represented class
