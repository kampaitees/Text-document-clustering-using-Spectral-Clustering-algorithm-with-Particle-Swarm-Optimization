# Text document clustering using Spectral Clustering algorithm with Particle Swarm Optimization (inclusion of PCA)

Team Members - <br>
__*VEDANT MEHRA - 171CO250 <br>
RISHI SHARMA - 171CO135*__

Document clustering is a gathering of textual content documents into groups or clusters. The main aim is to cluster the documents, which are internally logical but considerably different from each other. It is a crucial process used in information retrieval, information extraction and document organization. In recent years, the spectral clustering is widely applied in the field of machine learning as an innovative clustering technique. This research work proposes a novel Spectral Clustering algorithm with Particle Swarm Optimization (SCPSO) to improve the text document clustering. By considering global and local optimization function, the randomization is carried out with the initial population. This research work aims at combining the spectral clustering with swarm optimization to deal with the huge volume of text documents. The proposed algorithm SCPSO is examined with the benchmark database against the other existing approaches. The proposed algorithm SCPSO is compared with the Spherical K-means, Expectation Maximization Method (EM) and standard PSO Algorithm. The concluding results show that the proposed SCPSO algorithm yields better clustering accuracy than other clustering techniques

<h3>Install libraries / Set up environment</h3> 
Install jupyter notebook - https://jupyter.org/install <br>
Install Anaconda - https://docs.anaconda.com/anaconda/install/ <br>
NLTK - https://www.nltk.org/install.html <br>
gensim installation command in jupyter notebook - !pip install --upgrade gensim
<br>
numpy, pandas, matplotlib, scikitlearn are already included in Anaconda. <br>

<h2>How to run the code</h2>
Clone this repository and open the notebook in jupyter notebook.<br>
Now one can run each and every cell of the notebook. Furthur details of what each section of the code contains is given below.
The first section of the code contains preliminary work which is needed. We __*imported the libraries*__ that are required, then __*downloading stopwords*__ and the function for creating the __*tf-idf vector*__.<br>
The next section will __*use the imported Reuters dataset*__ and divide it into training and testing data, form the tf-idf vector from the training data. <br>
Now the section of __*Visualization*__ has importing gensim library, tokenising the single document text, converting the tokenised vector to pandas dataframe and then visualising the word embeddings.
Then we move to the __*Particle Swarm Optimization*__ section where we have a function for PSO algorithm.<br>
The next section is for __*Spectral Clustering*__ which will import necessary libraries, fit the data and calculate the Adjusted Random Index (ARI).<br>
The next section is __*our own ideas*__ which involves the idea of using __*Principle Component Analysis(PCA) on Affinity matrix with Euclidean Distance*__. Here we applied PCA on Affinity matrix with Euclidean Distance and then calculated the ARI for the model.<br>
The next section has our other idea which is to use __*Principle Component Analysis(PCA) on Affinity matrix with Gaussian Kernel*__. Here we applied PCA on Affinity matrix with Gaussian Kernel and then calculated the ARI for the model.<br>
The last section is the __*Comparison of Adjusted Rand Index*__ for various models. 
