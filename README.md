# Predicting Long Duration New Building Job Filings

Job filings that require numerous plan exams to approve consume scarce DOB resources and reduce the quality of City services.

Goal: Improve Department of Building (DOB) process efficiency and City services by speeding up time to approve job filings.

Objective of the predictive model: 

1. Label new job filings that are predicted to take many plan exams to approve.

2. Once job filings are labeled, they are given special consideration to speed up approval process.

## Data
New building (NB) job filings and plan exam data from January 2011 to the present. The outcome variable is a categorical variable based on the number of plan exams to approve a job filing. Greater than five plan exams is considered “high”, less than or equal to five plan exams is “low”.

Independent variables include DOB estimated fee, floor area, floor area ratio (FAR), number of dwellings, work types, community board, building height, occupancy classification, structural system description, zoning classification and lot detail.

## Model
Gradient Boosted Decision Trees

Tree algorithms are “learning” algorithms that comprise a series of logical decisions, similar to a flow chart, to determine which independent variables best predict the outcome variable.

Interpretive model: the algorithm can output the independent variables most correlated with a high number of plan exams. The independent variables that are highly correlated with the outcome variables are ranked from high to low according to their predictive power





