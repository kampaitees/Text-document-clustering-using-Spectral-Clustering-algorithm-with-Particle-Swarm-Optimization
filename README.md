# Text document clustering using Spectral Clustering algorithm with Particle Swarm Optimization (inclusion of PCA)

## Team Members
  - [RISHI SHARMA](https://github.com/kampaitees) - 171CO135
  - [VEDANT MEHRA](https://github.com/vmehra25) - 171CO250
<br>

## Libraries / Set up environment
  - [Jupyter Notebook](https://jupyter.org/install)
  - [Anaconda](https://docs.anaconda.com/anaconda/install/)
  - [NLTK](https://www.nltk.org/install.html/)
  - [Numpy](https://numpy.org/)
  - [Pandas](https://pandas.pydata.org/)
  - [Matplotlib](https://matplotlib.org/)
  - [Gensim](https://radimrehurek.com/gensim/)


## What things you need to install the software and how to install them

#### Following are the dependencies of python which you have to install in your system
 ``` 
  - python 3.6.8 
  - python pip 
 ```
#### After installing python and pip you have to just write  

  ```sh
    $ pip install 'below library names'
   ```
#### To install below dependencies
 ```
  - numpy
  - nltk
  - matplotlib
  - pandas
  - gensim
  - juyterlab 
 ```

## How to run the code
  - Clone this repository and open the notebook in jupyter notebook.<br>
  - Now one can run each and every cell of the notebook. Furthur details of what each section of the code contains is given below in furthur steps.<br>
  - The first section of the code contains preliminary work which is needed. We <b>imported the libraries</b> that are required, then <b>downloading stopwords</b> and the function for creating the <b>tf-idf vector</b>.<br>
  - The next section will <b>use the imported Reuters dataset</b> and divide it into training and testing data, form the tf-idf vector from the training data. <br>
  - Now the section of <b>Visualization</b> has importing gensim library, tokenising the single document text, converting the tokenised vector to pandas dataframe and then visualising the word embeddings.<br>
  - Then we move to the <b>Particle Swarm Optimization</b> section where we have a function for PSO algorithm.<br>
  - The next section is for <b>Spectral Clustering</b> which will import necessary libraries, fit the data and calculate the Adjusted Random Index (ARI).<br>
  - The next section is <b>our own ideas</b> which involves the idea of using <b>Principle Component Analysis(PCA) on Affinity matrix with Euclidean Distance</b>. Here we applied 
  - PCA on Affinity matrix with Euclidean Distance and then calculated the ARI for the model.<br>
  - The next section has our other idea which is to use <b>Principle Component Analysis(PCA) on Affinity matrix with Gaussian Kernel</b>. Here we applied PCA on Affinity matrix with Gaussian Kernel and then calculated the ARI for the model.<br>
  - The last section is the <b>Comparison of Adjusted Rand Index</b> for various models. 

## Link to Google Colab Notebook
[Click Here](https://colab.research.google.com/drive/1ErZ--e--kPaPP0fadfDNNDuaXbrN9T0X)