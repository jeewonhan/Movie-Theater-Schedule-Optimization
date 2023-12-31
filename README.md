## Introduction
This section of my portfolio showcases a project entitled "Saving Cinema: Designing Movie Theater Showing Schedules." This data mining project adheres to the CRISP-DM Model and was completed as part of EN.553.602: Research and Design in Applied Mathematics: Data Mining at The Johns Hopkins University in the Fall of 2023. The work was carried out under the mentorship of Drew Henrichsen, alongside collaborators Lucas Rozendaal, Sam Oberly, Jay Lawrence, and Jillayne Clarke.

As is likely evident, this repository is a work in progress. This is for two reasons:

1. Our work on this project will continue until the end of the 2023 calendar year.
2. While this project was a team effort, <ins>**I am in the process of reviewing and editing *all* code for efficiency and clarity, tailoring it to suit the standards of my personal portfolio**</ins>. The collaborative nature of the project led to several re-iterations of our work, resulting in duplicative, scattered, and at times disorganized work. The original repository for reference can be found [here](https://github.com/samob917/en553.602.FA23).

### Brief Project Overview
In the wake of the COVID-19 pandemic, the movie theater industry has grappled with significant financial setbacks, experiencing an 82% decrease in box office revenues from 2018 to 2019. Despite showing some signs of recovery, the projected box office for 2023 remains below pre-pandemic levels, prompting the business question for this project: "How can a movie theater company create the most profitable showing schedule for its theaters?" The primary objective is to construct a predictive model leveraging movie metadata, sourced from *TMDB*, *Box Office Mojo*, and other sources to predict box office revenue. This model aims to guide strategic decisions on showing schedule optimization by employing careful feature engineering and various techniques such as k-means clustering, spectral embedding, regression imputation, and more.

Additional information about the project's motivation, data sources, and modeling processes can be found in the Project Proposal and Data Preparation Report in [0. Deliverables](https://github.com/jeewonhan/Movie-Theater-Schedule-Optimization/tree/main/0.%20Deliverables). 

## Organization
Thus far, the project can be organized into 3 sections in accordance with the CRISP-DM model:

1. Business Understanding
2. Data Preparation
3. Data Understanding

For ease of access, major deliverables such as the Project Proposal and Data Preparation Report are found in 0. Deliverables.

## My Contributions
Other than the edits made to code as outlined in the Introduction, my key contributions to this project include

- 0. Deliverables: Primary author and editor on the [Project Proposal](https://github.com/jeewonhan/Movie-Theater-Schedule-Optimization/tree/main/0.%20Deliverables/Project%20Proposal) and [Data Preparation Report](https://github.com/jeewonhan/Movie-Theater-Schedule-Optimization/tree/main/0.%20Deliverables/Data%20Preparation%20Report).
- 2.1. Collect Initial Data: [2.1.3 Get TMDB Movie Details API Call](https://github.com/jeewonhan/Movie-Theater-Schedule-Optimization/blob/main/2.%20Data%20Understanding/2.1%20Collect%20Initial%20Data/2.1.3%20Get%20TMDB%20Movie%20Details/2.1.3%20TMDB%20Movie%20Details%20Call.ipynb)
- 2.3 Explore Data: [Exploratory Data Analysis](https://github.com/jeewonhan/Movie-Theater-Schedule-Optimization/tree/main/2.%20Data%20Understanding/2.3%20Explore%20Data)
- 3.3. Construct Data: [3.3.13 Genre Clustering Using Jaccard Similarity and Spectral Embedding](https://github.com/jeewonhan/Movie-Theater-Schedule-Optimization/blob/main/3.%20Data%20Preparation/3.3%20Construct%20Data/3.3.13%20Genre%20Clustering/3.3.13%20Genre%20Clustering%20by%20Jaccard%20Similarity.ipynb)
