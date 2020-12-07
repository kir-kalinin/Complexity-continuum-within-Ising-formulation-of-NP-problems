# Complexity-continuum-within-Ising-formulation-of-NP-problems

The minimisation of the Ising Hamiltonian for sparse and dense interaction matrices with exact and physics-inspired algorithms. 

The implemented Ising models include: 
- the Sherrington-Kirkpatrick, 
- the 3-regular maximum cut, 
- the Mobius ladder graphs,
- the rewired Mobius ladder graphs.

The interaction strengths can be taken from the unweighted, bimodal, and Gaussian distributions.

The available methods for solving the Ising model are:
- the exact commercial solver Gurobi (the free academic license is available at 
[Gurobi website](https://www.gurobi.com/downloads/?campaignid=2027425879&adgroupid=77414946451&creative=375332431098&keyword=gurobi%20academic%20license&matchtype=e&gclid=CjwKCAiAwrf-BRA9EiwAUWwKXkrNUZk9swkN-tmC-Z8gehq6tk7qrXMBcspOUDl2B2Lv5drmtF099BoCZFIQAvD_BwE)),
- the Hopfield-Tank neural networks (implemented in python and accelerated with numba).

Requirements: numpy, scipy, numba, gurobipy.

More details about simple and hard problems for the Ising optimisation could be found in the article:

[Kalinin, Kirill P., and Natalia G. Berloff. "Complexity continuum within Ising formulation of NP problems." arXiv preprint arXiv:2008.00466 (2020).](https://arxiv.org/abs/2008.00466)

Ps If you find the code useful for your studies please consider citing the above paper.
