# OneStepGD_asymptotics
code for Asymptotics of feature learning in two-layer networks after one gradient-step


$\texttt{theory.ipynb}$ contains the numerical implementation of the theoretical characterization of Result 3.3, taking as inputs the normalized learning rate $\tilde{\eta}$, sample complexity $\alpha_0$ for the first gradient step, activations $\sigma,\sigma_\star$, and readout regularization $\lambda$.

$\texttt{Simulations.ipynb}$ implement the corresponding numerical experiments, namely one large gradient-descent step on the first layer weights, followed by ridge regression on the readout weights.
