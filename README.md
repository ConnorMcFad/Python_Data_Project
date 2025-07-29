# Overview

Welcome to my analysis of the data job market, with special focus on data analyst roles. The analysis preformed was done to uncover insights into the data job market. It delves into what skills are in demand and what skills associated with higher salaries.

# Questions

1. What skills are most in demand for the 3 most popular data roles?
2. How are in-demand skills trending for Data Analysts?
3. How well do jobs and skills pay for Data Analysts?
4. What skills are optimal to learn?

# Tools Used
- Python
    - Pandas Library
    - Matplotlib Library
    - Seaborn Library
- Jupyter Notebooks
- VS COde
- Git & GitHub


# The Analysis

## 1. What are the most demanded skills for the top 3 most popular data roles?

To find the most demanded skills, I filtered the positions and found the top 5 skills for these roles. This query was utilized to uncover the most popular job titles and their top skills. This insight allows me to prioritize skills depending on which role I want to pursue.

View my notebook with corresponding code here:
[2_Skills_Count.ipynb](3_Project\2_Skills_Count.ipynb)

### Results 
![Visualization for top Skills](3_Project\Images\skill_demand_data_roles.png)


### Insights
- Python is a highly in demand, versatile skill, that is relevant across all three roles. It is present in over 72% of Data Scientist roles and 65% of Data Engineer roles. 
- SQL is the most requested skill for both Data Analysts and Data Engineers, with it being in over half of job postings.
- Data Engineers require more technical skills compared to their Datat Analyst and Data Scientist Counterparts, who are expected to be proficient in more general data management and analysis tools.

## 2. How are in-demand skills trending for Data Analysts?

I examined how the top skills present in data job listings changed over the year. This type of data exploration would be even more usefull across years, but this still provides some insights on which skills are trending. 

### Results
![Visualization for trending skills](3_Project\Images\skill_trend.png)

### Insights

While most skills stayed fairly consistent, the more rudementary skills like sql and excell actually trended downward. These skills are very foundational in most data jobs, and may be expected even when they are not directly listed. One other notable observations is that Python peaked at being present in over 30% of data job listings in August. The slight upward trend could have to do with the continued emergence of AI and Machine Learning models in the data world. Overall, the relative consistency of the demand for these skills emphasizes their importance and relevance for people seeking a career in the data industry.

## 3. How well do jobs and skills pay for Data Analysis?

## Salary Analysis for Data Jobs 

### Results
![Salary Distributions of Data Jobs in the US](3_Project\Images\salary_data_jobs.png)
*Box plot visualizing the salary distributions for the 6 main data job titles.*

### Insights 

- Job titles such as Data Architect and Machine Learning Engineer show significantly higher median salaries compared to roles like Data Analyst or Business Intelligence Analyst, indicating these are more specialized or senior roles in the job market.

- Data Scientist display wider interquartile ranges and more outliers, suggesting a broader salary spread — likely due to differences in company size, location, and experience levels.

- In contrast, roles like Data Analyst and Senior Data Analyst have narrower quartile boxes, implying more consistent pay ranges and standardization across industries.

## Highest Paid & Most Demanded Skills for Data

### Results
![Highest Paid and Most In-Demand Skills for Data Analysts in the US](3_Project\Images\skill_salary_analysis.png)

- There is great contrast in the top-paying skills and the most demanded skills. The top-paying skills (e.g., dplyr, bitbucket, gitlab, solidity) all have less than 4 job listings in this dataset. These tools are highly specialized and niche, suggesting that scarcity, rather than popularity, is a key driver of higher salaries.

- Popular tools like python, excel, and powerpoint appear in the most requested list, but they offer lower average salaries. This highlights that widespread knowledge of these tools leads to greater competition and less salary leverage.

- Skills like hugging face (used in NLP), solidity (used in blockchain), and gitlab indicate cutting-edge tech familiarity is rewarded with higher pay — likely due to fewer qualified candidates and emerging market demand.

- The most requested tools (tableau, sql server, power bi) reflect the continued demand for dashboarding and data reporting, showing how businesses prioritize tools that support decision-making and business intelligence workflows.

## 4. What is the most optimal skill to learn for Data Analysts in the US?


### Results

![Most Optimal Skills for Data Analysts in the US](3_Project\Images\optimal_skill.png)
*A scatter plot visualizing the most optimal skills (high pay & high demand) for Data Analysts in the US*

### Insights 

- Most of the programming skills tend to cluster at higher salary levels comopared to other categories, indicating that programming expertise might offer greater salary benefits within the data analytics field.

- Analyst tools, including tableau and Power Bi, are prevalent in job postings and offer competitive salaries, showcasing that visualization and data software are crucial for current data roles.

- The database skills featured are associated with high salaries; however, they are not in a large number of job postings. They seem to be specialized skills that command higher pay, with fewer job listings.


# What I learned

Throughout this project, I deepened my understanding of the data job market while enhancing my python skills, especially in data manipulation and visualization. I learned that while specialized skills are associated with higher salaries, they are not relevant to a majority of job listings. A strong background in basic skills like SQL, Excell, and Word coupled with more advanced programatic (Python, R, etc.) and data visualization/management skills (Tableau, Power Bi) will provide prospective job candidates with more job opportunities as they learn even more specialized skills.

