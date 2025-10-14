In this project, we try to solve the minimisation problem of Submodular functions using the Gaussian random zeroth-order oracles and a zeroth-order gradient descent algorithm.

In this folder, there are two Python notebooks. In the file "subM.ipynb", you can find the code for offline semi-supervised clustering via minimisation of a submodular cost function. The ZO solver and subgradient solver are implemented to solve the minimisation problem.

In the file "subM2.ipynb", you can find the code for the Minimisation of the logdet function via the subgradient method and the ZO solvers with exact and approximate queries of the Lovasz Extension. Then, the offline semi-supervised clustering is solved using the subgradient and the ZO solvers with exact and approximate queries of the Lovasz Extension. The goal was to see the performance of the ZO solvers with queries of different approximations of the Lovasz extension. Then, the problem of online semi-supervised clustering is solved using the subgradient and the ZO solvers with exact and approximate queries.

These tests are part of numerical examples of a paper manuscript whose link will be announced in the near future.
