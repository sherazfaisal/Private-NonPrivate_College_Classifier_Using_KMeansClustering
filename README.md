# Private/NonPrivate College Classifier Using_KMeansClustering
We have imparted the "News and World Reports College Data" to get more insights about the characteristics of private and non-private colleges. We have developed a model that could predict or classify a college weather it is private or non-private looking at its distinct features.

We will use a data frame with 777 observations on the following 18 variables.

Private A factor with levels No and Yes indicating private or public university

Apps Number of applications received

Accept Number of applications accepted

Enroll Number of new students enrolled

Top10perc Pct. new students from top 10% of H.S. class

Top25perc Pct. new students from top 25% of H.S. class

F.Undergrad Number of fulltime undergraduates

P.Undergrad Number of parttime undergraduates

Outstate Out-of-state tuition

Room.Board Room and board costs

Books Estimated book costs

Personal Estimated personal spending

PhD Pct. of faculty with Ph.D.’s

Terminal Pct. of faculty with terminal degree

S.F.Ratio Student/faculty ratio

perc.alumni Pct. alumni who donate

Expend Instructional expenditure per student

Grad.Rate Graduation rate

We have implemented data visualization techniques to the dataset to get the useful insights about private and non-private colleges. Here is the sneakpeak:


![Image of Yaktocat](https://hmp.me/dbu1)

![Image of Yaktocat](https://hmp.me/dbu2)

We have used KMeansClustering as a clustering algorithm for modeling the data. We have made some preprocessing before applying the model. Here is the classification report and confusion matrix of applied model for the purpose of model evalution

![Image of Yaktocat](https://hmp.me/dbu0)
