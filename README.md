Project Intro/Objective

The project used unspurvised learning to analyze a dataset of songs, and their lyrical features. This is a real dataset of songs from 1950 to 2011. 

Within this project, I will create a comprehensive machine learning pipeline that satisfies the patterned steps of a classic machine learning project. This entails:

● beginning with hypothesis formulation through EDA,
● completing data cleaning, pre-processing, & dimensionality analysis,
● and concluding with model generation, sample prediction, and a report.

Methods Used

Inferential Statistics
Machine Learning (Elbow Plot and Kmeans)
Data Visualization
Predictive Modeling

Technologies
Python
Pandas, jupyter
Project Description


REPORT

i. Which insights did you gain from your EDA? Were any columns highly correlated? If so, name them.

Based on the Genre type, pop is the most popular music. Amount the frequency by topic, sadness is the most popular music type. Based on the correlation matrix of numerical variables, the most correlated columns are column len and column obscene. The correlations score is 0.44.


ii. How did you determine which columns to drop or keep? If your EDA informed this process, explain which insights you used to determine which columns were not needed.

I mainly based on whether the columns are categorical columns or numerical columns. I took out all categorical columns. 


iii. What was the optimal number of clusters in your cluster model? Explain how you determined this value.


I used Kmeans to find the optimal number of clusters. Without scaling, the optimal number of clusters is 4 based on the Elbow Plot graph. With scaling, the optimal number of cluster that I choose is 8. With my three predations, the optimal number of clusters is 4. 

iv. Take a look at the respective songs that fell into your clusters.
Describe these clusters in human terms to the best of your ability
using the columns in your dataset (for example high-gospel songs,
low-gospel songs, etc). Feel free to listen to these songs as well to
get a sense of what nuance your algorithm picked up on.

For my 4 without scaled clusters analysis:
cluster 0 has #the fewest lyrics, high dating, and very low violence. It tends to be longer age. Very slow movement. The lowest obscene.
Cluster 1 has the longest lyric, high dating, the highest violence, and the highest obscene. 
Cluster 2 has # fewer lyrics, less obscene, high violence,
Cluster 3 has #long lyrics, low dating, high obscene, and the highest violence.
