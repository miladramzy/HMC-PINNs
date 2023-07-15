# HMC-PINNs

### Effect of PDE log-likelihood std on BPINN's prediction and confidence interval
A large std for the PDE log-likelihood implicitly tells the model that the known governing law might not be as accurate and thus, the model's predictions become more uncertain (large confidence intervals). This is more evident in regions far from the initial and boundary points, where the model solely relies on the PDE equation to learn the system's behaviour (green curve).
<img src="assets/Effect of PDE std.svg" width="1000">
