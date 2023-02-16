# Quantum Metric Tensor
A version of the Wolfram Mathematica code used in my PhD project to compute the Quantum Metric Tensor, its determinant, and its scalar curvature for the anisotropic Lipkin-Meshkov-Glick model. The Hamiltonian is

$$ \hat{H} = -2 h \hat{J}_z - \frac{1}{j} (\hat{J}_x^2 + \gamma \hat{J}_y^2), $$

the parameters are $x={x^i}=(h,\gamma)$, and the corresponding deformation operators are

$$ \hat{O}_h = \frac{\partial \hat{H}}{\partial h} = -2\hat{J}_z, $$

and

$$ \hat{O}_{\gamma} = \frac{\partial \hat{H}}{\partial \gamma} = -\frac{1}{j} \hat{J}_y^2. $$

The default value of the pseudospin is $j=20$. First compute the three components of the QMT using the G11.nb notebook, then run Determinant.nb and, finally, run R.nb to find the Ricci scalar.
