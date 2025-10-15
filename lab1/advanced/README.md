# Mental Health in Tech Survey Analysis

This project analyzes data from the 2014 Mental Health in Tech Survey, which explores attitudes towards mental health and the frequency of mental health disorders in the technology workplace.

## Dataset

The dataset contains responses from tech workers around the world. Key columns include:
- **Timestamp**: Date and time of response
- **Age**: Respondent's age
- **Gender**: Gender (binary for analysis)
- **Country/State**: Location
- **Self_employed**: Employment type
- **Family_history**: Family history of mental illness
- **Treatment**: Whether the respondent has sought treatment
- **Work_interfere**: Impact of mental health on work
- **No_employees**: Company size
- **Remote_work**: Remote work status
- **Tech_company**: Whether the company is in tech
- **Benefits, Care_options, Wellness_program, Seek_help, Anonymity, Leave**: Workplace support and policies
- **Mental_health_consequence, Phys_health_consequence**: Perceived consequences
- **Coworkers, Supervisor**: Support at work
- **Mental_health_interview, Phys_health_interview, Mental_vs_physical, Obs_consequence**: Attitudes towards mental and physical health
- **Comments**: Free text responses

## Analysis Overview

Notebook covers:
- Data cleaning (e.g., filtering age, standardizing gender)
- Distribution of survey participants by country and state
- Gender distribution
- Self-employment and treatment rates
- Family history and its impact on seeking treatment
- Company size and workplace benefits
- Age distribution by treatment status (including boxplots)
- Remote work statistics
- Correlations between variables (e.g., family history vs. treatment, company size vs. benefits)

## How to Run

1. Install required Python packages:
   ```
   pip install pandas matplotlib seaborn numpy
   ```
2. Place `survey.csv` in the same directory as the notebook.
3. Open and run `mental_health_exploration.ipynb` in Jupyter or VS Code.

## Author

Jan Jochymczyk  
[GitHub](https://github.com/janek-j)

## Data Source

[Kaggle: Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey?resource=download)