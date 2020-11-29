# Text document clustering using Spectral Clustering algorithm with Particle Swarm Optimization (inclusion of PCA)

Team Members - <br>
__*VEDANT MEHRA - 171CO250 <br>
RISHI SHARMA - 171CO135*__

Document clustering is a gathering of textual content documents into groups or clusters. The main aim is to cluster the documents, which are internally logical but considerably different from each other. It is a crucial process used in information retrieval, information extraction and document organization. In recent years, the spectral clustering is widely applied in the field of machine learning as an innovative clustering technique. This research work proposes a novel Spectral Clustering algorithm with Particle Swarm Optimization (SCPSO) to improve the text document clustering. By considering global and local optimization function, the randomization is carried out with the initial population. This research work aims at combining the spectral clustering with swarm optimization to deal with the huge volume of text documents. The proposed algorithm SCPSO is examined with the benchmark database against the other existing approaches. The proposed algorithm SCPSO is compared with the Spherical K-means, Expectation Maximization Method (EM) and standard PSO Algorithm. The concluding results show that the proposed SCPSO algorithm yields better clustering accuracy than other clustering techniques

## Install libraries / Set up environment
  - [Jupyter Notebook](https://jupyter.org/install)
  - [Anaconda](https://docs.anaconda.com/anaconda/install/)
  - [NLTK](https://www.nltk.org/install.html/)<br>
  - gensim installation command in jupyter notebook
  ```sh
    $ !pip install --upgrade gensim
   ```
  - numpy, pandas, matplotlib, scikitlearn are already included in Anaconda. <br>

<h2>How to run the code</h2>
1) Clone this repository and open the notebook in jupyter notebook.<br>
2) Now one can run each and every cell of the notebook. Furthur details of what each section of the code contains is given below in furthur steps.<br>
3) The first section of the code contains preliminary work which is needed. We <b>imported the libraries</b> that are required, then <b>downloading stopwords</b> and the function for creating the <b>tf-idf vector</b>.<br>
4) The next section will <b>use the imported Reuters dataset</b> and divide it into training and testing data, form the tf-idf vector from the training data. <br>
5) Now the section of <b>Visualization</b> has importing gensim library, tokenising the single document text, converting the tokenised vector to pandas dataframe and then visualising the word embeddings.<br>
6) Then we move to the <b>Particle Swarm Optimization</b> section where we have a function for PSO algorithm.<br>
7) The next section is for <b>Spectral Clustering</b> which will import necessary libraries, fit the data and calculate the Adjusted Random Index (ARI).<br>
8) The next section is <b>our own ideas</b> which involves the idea of using <b>Principle Component Analysis(PCA) on Affinity matrix with Euclidean Distance</b>. Here we applied 9) PCA on Affinity matrix with Euclidean Distance and then calculated the ARI for the model.<br>
10) The next section has our other idea which is to use <b>Principle Component Analysis(PCA) on Affinity matrix with Gaussian Kernel</b>. Here we applied PCA on Affinity matrix with Gaussian Kernel and then calculated the ARI for the model.<br>
11) The last section is the <b>Comparison of Adjusted Rand Index</b> for various models. 
