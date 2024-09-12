# Digital Screen Time Analysis and Well-Being Correlation

This project aims to analyze the effect of digital screen time (computers, smartphones, TV, video games) on the well-being of adolescents using real-world datasets. The study leverages data science tools to highlight the potential impacts of high screen time on psychological symptoms and behavioural outcomes.

## Objectives:
1. Descriptive Analysis:
Explored the demographic factors (gender, minority status, deprivation index) influencing screen time.
Analyzed how well-being indicators differ based on screen time across weekdays and weekends.

2. Inferential Analysis:
Performed hypothesis testing to determine if there is a significant difference in well-being scores between high and low screen time users.
Done Kruskal-Wallis Test: Non-parametric Test for Well-being and Screen Time (as it is ordinal data)


## Repository Structure
- `/data/`: Contains the dataset used for analysis.
- `/scripts/`: Python scripts for different stages of the project.
  - `screen-time-analysis-descriptive.ipynb`: Descriptive statistics and visualizations for well-being scores and screen time.
  - `screen-time-analysis-inferential.ipynb`: Inferential statistical tests (T-test, Kruskal-Wallis) to find significant differences in well-being indicators.
- `/results/`: Contains output files such as graphs and summary reports.

### Notes: 
1. Download the data or change the path in the code as necessary.
2. Run the descriptive-analysis script first to have the **merged_data** created which is used in the other script directly.



