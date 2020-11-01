This notebook implements multiple linear regression with Ridge Regularization (Tikhonov) to identify best hyperparameter (lambda)

Regularization is added to reduce susceptability to noise:


Notes

– Without regularization: eigenvalues of linear system may be arbitrarily close to 0 and the inverse may have arbitrarily large eigenvalues.

– With Tikhonov regularization, eigenvalues of linear system are ≥ λ and therefore bounded away from 0. Similarly, eigenvalues of inverse are bounded above by 1/λ.
