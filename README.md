# fictional-palm-tree
ALX-T 1
ALX-T PROJECT REPORT

ABSTRACT
This project aims to perform an in-depth analysis on the datasets given. We aim to understand our dataset before any further action can be done, for example, any algorithms formulated. 
In some instances, Data science is not really needed to solve all challenges we encounter and as such, it is important to analyze the problem statement and the data before we end up using personnel and finances performing a job that could have been done easily and using less finances. 

1. CONTEXT
There are many movies currently in the market; different genres, facing different popularity levels, having different budgets injected to make them a reality. The idea comes down to trying to help 2 parties; the producers and the consumers. 
Is there a way we can be able to help the consumers by suggesting which movies they are likely to enjoy?
Is there a way we can advise the producers on which movies to invest in based on the popularity levels so that they can reap more money?
Is there a level of correlation between the features?
There are just some of the questions that we will seek to answer using our current dataset.


The attached link entails a Git repository with the Data Report and Analysis.
https://github.com/Kathi3/fictional-palm-tree 

2. CRISP-DM
In this ALX-T project, the CRISP-DM model is used, which is a leading data mining
methodology. CRISP-DM has provided the guidelines that have enabled the execution of this
project in an organized and transparent manner. This model groups all tasks into six phases as
listed below.
● Business understanding
● Data understanding
● Data preparation
● Modeling
● Evaluation
● Deployment

3.1. BUSINESS UNDERSTANDING

The main task is to use the data that has been provided to answer the questions we set out to understand and to visualize the data so as to make it easier for non-data scientists  to understand and follow our work.
Our resources are as seen below.

● Personnel- an aspiring data scientist
● Data - Provided Dataset (tmdb Movies)
● Software- Jupyter Notebook

The project is scheduled to be evaluated and corrected if need be by completed by 21st August 2022.

3.2 DATA MINING OBJECTIVES & UNDERSTANDING
Some of our data mining objectives include:
The kind of entertainment the population likes based on the genre most liked.
Do these genres change from year to year?
Is there a correlation between the most popular genre with the revenues?
Are there any other factors that influence the revenues?.
Can we recommend movies to invest in/for consumers to watch based on past trends of revenues earned/popularity trend?

4. DATA UNDERSTANDING
The data used in this project were provided as follows:
● Dataset Source - Provided by ALX-T
The project is done  on Jupyter Notebook .
On this platform, the data needs to be loaded before we proceed.
a) Importing the necessary libraries into Jupyter Notebook.
Next, we proceeded to load the dataset 
The data provided has  21 columns and 10866 rows. 

DATA WRANGLING
Before analyzing the data, there is a need to understand the nature of the data presented for
visualization.
The dataset had some null values, for example production_companies and homepage.
Seeing as none of the null values interfere with our objectives, the decision made was to drop them as they would interfere with the work while bringing no analysis benefits.
There was a single duplicated column and as such, the column was dropped.
We did an analysis to determine which genre had the most counts and it showed ‘comedy’ and ‘drama’ were tied in first place.

DATA EXPLORATION
The idea of this section is to create visualizations that can actually prove or disprove the objectives we set out to achieve to help us make more informed decisions.
By the use of scatter plots, we are able to find out the features that actually affect the revenue.
Features such as popularity and the budget allocated seem to positively affect the revenue while features like revenue barely have any influence on the revenue.


Performing an analysis of the categorical columns is performed to get to understand the vastness of each genre.


CONCLUSIONS & RECOMMENDATION

From the descriptive analysis done on the data we can see there are features that have a correlation and help us answer the questions we set out to answer.
 
1. The kind of entertainment the population likes best - Drama & Comedy Genres tie for top spot.
2. Does this genre change from year to year? Unable to determine since the data is not split into years. As such there is a need for more descriptive data to be able to study the trend and perform time series.
3. Is there a correlation between the most popular genre with the revenues? Yes. A genre that is highly popular tends to earn more revenues.
4. Are there any other factors that influence the revenues?. There are factors that also seem to lead to an increase in revenues eg. budget. When more finances are allocated to a genre, the returns it yields are also high. An equivalent pay day
5. Can we recommend movies to invest in/for consumers to watch based on past trends of revenues earned/popularity trend? Yes but with a curvature. We can recommend movies to watch based on past popularity but there is a need to apply machine learning algorithms to predict the trend in terms of customers and investors.

Recommendation
While descriptive analysis forms a basis to understand the data, there is a need to apply more sophisticated algorithms to have more solid predictions

Followup Questions
Is the data complete and right? No The data could have been better. The missing values and lack of columns that could have added important information lead to a half baked analysis.
