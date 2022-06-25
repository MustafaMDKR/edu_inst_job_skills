
# Educational Institute Usecase:

## A) Problem Statement

Our Client is an IT educational institute. They had reached out with the following:

"IT jobs and technologies evolving quickly. This makes our field to be one of the most interesting out there.
But on the other hand, Such fast development confuses our students. They don't know which skills they need to learn for which job."

"D I need to learn C++ to be a data scientist?" "Do DevOps and System Admins use the same technologies?"
"I really like Javascript; can I use it in Data Analytics?"
Those are some questions asked by our students.

Could you please develop a data-driven solution for our students to answer such questions? They mostly want to understand the relationships between the jobs and the technologies.


## B) Business Case

Our client needs KPIs that we will positivly impact.

 1. Higher enrollment rate due to higher certainty
 2. Decrease in drop-out rate
 3. Time saved for the academic advisors


## C) Data

Which Data source will we use? Where tp start.

Dataset Search from Google
https://datasetsearch.research.google.com


## Be careful:

- Be through the quality checks
- Make sure your Data will be updated on a regular base


### Data Source 

chosen: Stack Overflow developers survey
https://insights.stackoverflow.com/survey/2021



## Foundations

 ### 1. Legal & Data privacy check
		-Global:
		-Local:


 ### 2. Structturing Our Project
	https://github.com/drivendata/cookiecutter-data-science


 ### 3. Our Git Repo


 ### 4. Processing

	00_Explatory Notebook
	01_Preprocessing

# Our Analytics Questions

## As soon as we ask the right question we will get to a good answer.
## We will start with our goal of this project

	- General:
		- Total number of  answers
		- Geographical distributions
		- Missing answers
	- Skills:
		- Frequency of each skill
		- How are the skills correlated with each other
	- Jobs:
		- Frequency of each job
		- How are the jobs correlated with each other
	- Relation:
		- How are the skills correlated with the jobs
		- What is the specificity of each skill to job


# Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------
