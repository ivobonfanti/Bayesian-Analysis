# Bayesian-Analysis

This project aims at modelling financial contagion between the
main European banks via Bayesian analysis. The financial risk is
proxied by the change in credit default swap (CDS) spreads over the
time, while the underlying model is a Bayesian Vector Autoregres-
sive (BVAR). For the coefficients, to handle the typical VAR over-
parameterization, a Minnesota prior distribution is considered, while
an Inverse-Wishart distribution incorporates prior beliefs about the
second moment of the residual term. Once derived the conditional pos-
terior distributions for both parameters, a Gibbs sampler algorithm is
implemented to simulate realizations. The obtained results are even-
tually used to forecast and to extract a network describing financial
interconnectedness.
