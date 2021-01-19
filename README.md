# Analysis of the operator's efficiency in a virtual communication company.

*The analytical task and dataset used in this project are dummies. The project was created exclusively for practice.*

**The virtual communications company wants to improve the company's service standards and renegotiate employee agreements.
For these purposes, the company is developing a new feature that will provide supervisors with information about the least efficient operators.**

This repository is an attempt to answer who are inefficient operators and by what criteria to define them. 

The project consists of 4 stages: 
* Project Decomposition
* Project Implementation
* Project Presentation
* Project Dashboard

**Decomposition of the project**, in fact, is the analysis of the task. It is a technique that involves defining and breaking down tasks into steps and substeps necessary to achieve the goal of the task.

Decomposition is a highly recommended step in data analytics projects that provides a general deep understanding of the task, helps the team work together, and saves a lot of time for the next phase, the project implementation stage. Decomposition is a great plan to achieve your goals without wasting time and human resources. 

In terms of **Project Implementation**, decomposed project stages are performed. However, at the same time, the data analysis process is flexible, which means that during data preprocessing and detailed exploratory data analysis, new results can change planned steps.

***Project Implementation. Content***:
1  Project overview
1.1  Telecom Operators
1.2  Project goal 
1.2.1  Description of the data
1.3  Table of Contents
2  Project implementation
2.1  Project settings
2.1.1  Importing libraries
2.1.2  Functions - helpers :)
2.1.2.1  eda_df()
2.1.2.2  plot_histogram_columns()
2.1.2.3  plot_boxplot_columns()
2.1.2.4  dtype_converter()
2.1.2.5  get_day()
2.1.2.6  check_hypothesis()
2.1.2.7  write_df_to_csv()
2.1.2.8  check_file_exist()
2.1.3  Data sources
2.2  Data Overview and Preprocessing
2.2.1  The telecom_operators dataset
2.2.1.1  Preliminary overview
2.2.1.2  Missing values
2.2.1.3  Conversion of data types
2.2.1.4  Distributions
2.2.1.5  Outliers
2.2.1.6  Studying and removing duplicates:
2.2.1.7  Conclusion
2.2.2  The telecom_clients dataset
2.2.2.1  Preliminary overview
2.2.2.2  Distributions
2.2.2.3  The shares of customer's tariff plan
2.2.2.4  Conclusion
2.3  Exploratory Data Analysis (EDA)
2.3.1  The shares of internal and external calls
2.3.2  The number of total calls per day
2.3.3  Daily number of working operators
2.3.4  Daily number of clients using the services
2.3.5  An average number of customers per operator they serve.
2.3.6  Average daily number of calls and their duration per operator.
2.3.7  The number of missed calls
2.3.8  Dynamics of waiting time
2.3.9  The number of outgoing calls
2.3.10  Dynamics of some absolute and average values
2.3.11  Conclusion
3  Metrics of Operator Efficiency
3.1  Setting standards
3.2  Efficiency calculation.
3.2.1  Preparing dataset
3.2.2  Efficiency calculation.
3.3  Conclusion
3.3.1  Overview
3.3.2  Inefficient operators
4  Hypotheses
4.1  Preparing for A / B testing
4.2  A/B Testing
5  Presentation
6  General conclusion and recommendations

***Project Presentation*** is published on Google Drive.[Link to the presentation](https://drive.google.com/file/d/1k7qah1ILyRBgRSIR5RXV4E0vntf50FLc/view?usp=sharing)

***Project Dashboard*** is published on Tableau Public. [Link to the dashboard](https://public.tableau.com/views/Telecomoperatorsefficiency/TelecomOperatorsEfficiency?:language=en&:display_count=y&:origin=viz_share_link)


