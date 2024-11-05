README
Our repo contains three models: one a sample model produced by ChatGPT, another a sample model from another source, and the other a model we wish to create on our own using the other as a guide. Our code involves producing synthetic data based on a factor analysis model, which includes randomly generated observed data, latent factors, noise, and the loadings matrix. It then runs the Expectation-Maximization algorithm to iteratively update estimates for the true loadings matrix and noise. Lastly, our code shows the difference between our estimated loadings matrix and the true loadings matrix, and we included a scatter plot of our synthetic data. Since we are making our own data rather than using a pre-existing dataset, there is no data that is needed to be accessed or stored. Our model was beneficial in helping us learn more about how latent parameters affect the data being generated as we were able to alter the variables in our model and observe the effect it had on the generating process.
The software dependencies required to run this code are numpy and matplotlib. To reproduce our results, all one needs to do is run the Jupyter Notebook, which is named baseline_model_notebook.ipynb. 

References:

https://gregorygundersen.com/blog/2018/08/08/factor-analysis/#ghahramani1996algorithm
Ghahramani, Z., & Hinton, G. E. (1996). The EM algorithm for mixtures of factor analyzers. Technical Report CRG-TR-96-1, University of Toronto.
https://github.com/je-suis-tm/machine-learning/blob/master/factor%20analysis.ipynb
