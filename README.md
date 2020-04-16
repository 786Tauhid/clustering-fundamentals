# clustering-fundamentals
# In this reposetry it contains two files:
1. clustering fundamentals
2. extracting dominant colors
# Clustering fundamentals:
1. i have write code from scracth for clustering 
2. used k-means ++ from sckit learn
3. i have seen that k-means not perform well on complex data so i used (DBSCAN) Density Based Spatial Clustering of Applications with Noise
4. in clustering algorithm there are mainly 4 steps:
    1. randomly initialize k-centers where k is number of clusters we want
    2. E-step :assigning each point of dataset to randomly assign centers/clusters
    3. M-step: update the centers/clusters location by taking mean of the data which are present in the given clusters/centers
    4. repeat step 2(E-STEP) and step 3(M-STEP)
    * E-step means expectation step
    * M-step means maximization step
# dominant colors extraction:
* in this project i have taken some clusters/colors and taken one image of elephant
* i have extracted dominant colors for every pixel of elephant image 
