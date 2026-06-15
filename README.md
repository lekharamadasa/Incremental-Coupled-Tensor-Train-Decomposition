# Incremental-Coupled-Tensor-Train-Decomposition
A coupled tensor decomposition is the joint factorization of multiple datasets expressed in the
form of coupled tensors, which share one or more common latent factors. The coupled tensor
decomposition improves the accuracy of sparse tensor completion by sharing information from
the coupled modes, and finds applications in recommender systems, link prediction systems,
computer vision etc., The existing coupled tensor decomposition methods are based on CP and
Tucker decompositions. In the proposed thesis, the tensor-train(TT) decomposition is used for
efficient coupled tensor decomposition, since TT decomposition shows linear complexity and
stable results for higher order tensors. The alternating least squares (ALS) algorithm is used
to solve the optimization problem of coupled tensor-train decomposition. To handle live or
real-time data, an efficient incremental tensor-train decomposition has been extended to cou
pled tensor-train multi-order incremental decomposition. The incremental approach overcomes
the problem of repetitive decomposition of previous data when new data is added, and thus
reduces the computational complexity. The experimental results on movielens and synthetic
dataset shows that the coupled TT decomposition is efficient in tensor completion. From the
theoretical and experimental results on movielens dataset, it shows that, the incremental cou
pled tensor-train decomposition takes approximately 2.5x times less execution time compared
to non incremental coupled tensor-train decomposition, and their mean absolute error is nearly
equal
