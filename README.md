# Sparse Random Feature Expansion
**Paper:** Generalization Bounds for Sparse Random Feature Expansions

**Authors:** Abolfazl Hashemi, Hayden Schaeffer, Robert Shi, Ufuk Topcu, Giang Tran, and Rachel Ward

**Link:** https://arxiv.org/abs/2103.03191

**Algorithm:** We introduce a new framework for approximating high-dimensional functions, called the Sparse Random Feature Expansion (SRFE). The choice of basis is inspired by the random Fourier feature method (by Rahimi and Recht), which uses a basis of comprised of simple functions with randomized parameters. We incorporate sparsity in the model (via using a small number of terms from a large feature space to represent dominate behavior and via sampling random low order interactions between variables) and solve the corresponding basis pursuit problem. In the paper, we provide uniform bounds on the approximation error and generalization bounds for functions in a certain class depending on the number of samples and the distribution of features (using techniques from compressive sensing). We show that the SRFE outperforms shallow networks in several scientific machine learning tasks, especially in the case where measurements are expensive and scarce.

**Test file:** 
SRFE_Example1.ipynb -- Approximate an order-2 function using SRFE (see Figure 1 in the paper): 

  `f(x_1,...,x_{10}) = (1/10)* \sum\limits_{k=1}^9 exp(-x_k)^2/(1+x_{k+1}^2).`
  
  The code presents an example for Algorithm 2.1 and Algorithm 3.1.
  
