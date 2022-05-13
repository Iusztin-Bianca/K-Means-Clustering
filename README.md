# K-Means-Clustering
This project was done in a machine learning course: Python for Data Science and Machine Learning Bootcamp.
K Means Clustering is an unsupervised learning algorithm that tries to cluster data based on their similarity.
Unsupervised learning means that there is no outcome to be predicted, and the algorithm just tries to find patterns in the data.
In k means clustering, we have to specify the number of clusters we want the data to be grouped into.
The algorithm randomly assigns each observation to a cluster, and finds the centroid of each cluster.
Then, the algorithm iterates through two steps: Reassign data points to the cluster whose centroid is the closest, and calculate the new centroid of each cluster.
These 2 steps are repeated untill the within cluster variation cannot be reduced any further.
The within cluster variation is calculated as the sum of the euclidian distance between the data points and their respective cluster centroids.

For this project, we will attempt to use KMeans Clustering to cluster Universities into two groups: Private and Public.
In this data set, we have labels, but they won't be used for the KMeans clustering algorithm(we will use them just to get an idea of how well the algoritm performed).

THE DATA
We will use a data frame with 777 observations on the following 18 variables:
Private A factor with levels No and Yes indicating private or public university,
Apps Number of applications received,
Accept Number of applications accepted,
Enroll Number of new students enrolled,
Top10perc Pct. new students from top 10% of H.S. class,
Top25perc Pct. new students from top 25% of H.S. class,
F.Undergrad Number of fulltime undergraduates,
P.Undergrad Number of parttime undergraduates,
Outstate Out-of-state tuition,
Room.Board Room and board costs,
Books Estimated book costs,
Personal Estimated personal spending,
PhD Pct. of faculty with Ph.D.’s,
Terminal Pct. of faculty with terminal degree,
S.F.Ratio Student/faculty ratio,
perc.alumni Pct. alumni who donate,
Expend Instructional expenditure per student,
Grad.Rate Graduation rate.
