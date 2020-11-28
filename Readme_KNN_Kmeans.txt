This Project consists of multiple 
Algorithms like :
Knn, Kmeans which have been developed from scratch on datasets generated randomly.

Kmeans: 
 Implement a k-means clustering algorithm.
Used the following parameters to generate 2D Gaussian random samples for different clusters.
μ1= [−3,0], μ2= [3,0], μ3= [0,3],Σ =[10.750.751](1)1.
functioncluster = mykmeans(X, k) clusters dataX into k clusters.
Used `2-norm of vectors to compute the distance between different samples.
Generated X using the parameters above, and the ground truth for cluster centers and cluster assignments. 
 shows data from  3  different clusters simultaneously.
Generated N= 300 for each cluster and tested my implementation on the synthetic data with different k= 2,3,4,5.
Visualized the changes of clustering result and cluster centers, computed clustering accuracy 
when k= 3. computed accuracy of the estimated cluster centers when k= 3
Then, changed the μ to μ1= [−2,0], μ2= [2,0], μ3= [0,2], generated new X and tested k-means algorithm. 
Generated N= 300 for each cluster and tested it on the synthetic data with different k= 2,3,4,5.  Visualized the changes of clustering result and cluster centers, computed clustering accuracy when k= 3.  Compute accuracy of the estimated cluster centers whenk= 3

KNN: 
Implement k-NN algorithms for classification.
The function class = myknnclassify(train, test, k)that classifies the class of input test given  a  training set train using k-NN  classifier  where ki s  the  number  of neighbors.   Used parameters to generate 2D Gaussian random samples for different clusters. μ0= [1,0], μ1= [0,1], Σ0=[10.750.751],Σ1=[1−0.50.51].
Generated N= 200 training samples for each class and assigned class labels 0 and 1 for each class. Did the same for testing samples; generated N= 50 for each class of testing set to evaluate the model.
The  first  2  columns  in train are 2D  Gaussian  random  data  and  the  last  column is the class label.  Used `2-norm of vectors to compute distance between different samples. 
Tried out different k= 1,2,3,4,5,10,20 to test k-NN classifier.  
Showed the changes of accuracy w.r.t.  the k .
function value = myknnregress(X, test, k)that regresses the target value of  input test given a  training  set train using k-NN regressor where k is  the number of  neighbors.This time, used the following parameters to generate 2D Gaussian random data xμ0= [1,0],Σ0=[10.750.751] and assigned target values of Gaussian random noise with σ= 0.5.
Generated N= 300 samples for training and 100 for testing sets. 
The first 2 columns intrain are 2D Gaussian random data and the last column is the target value.
Used `2-norm of vectors to compute distance between different samples.  Tried out different k= 1,2,3,5,10,20,50,100 to test k-NN classifier.
Showed changes of accuracy in average`2-norm w.r.t.  the k.