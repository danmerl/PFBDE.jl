# PFBDE.jl

"Parameter Free Bayesian Density Estimation" (PFBDE) is a neat paper by P. Richard Hahn (2016) [http://faculty.chicagobooth.edu/richard.hahn/PFBDE.pdf] that proposes some compelling new approaches to Bayesian model specification and inference.  

PFBDE.jl provides Julia notebooks that reproduce some of the examples and figures from that paper.  The notebooks are self documented, but in the unlikely event of woeful inscrutability, here's the intent:

* `beta_bernoulli_example.ipynb`: Demonstrates the equivalence of density estimates produced by samples obtained from a Bernoulli posterior prediction rule and those obtained [analytically] via the standard Beta-Bernoulli conjugate model.
* `gaussian_known_variance_example.ipynb`: Demonstrates the equivalence of density estimates produced by samples obtained from a Gaussian posterior prediction rule and those obtained [analytically] via the standard Normal-unknown-mean-known-precision conjugate model.
* `kernel_density_estimate_example.ipynb`:  Implements the predictivist take on Bayesian kernel density estimation.
