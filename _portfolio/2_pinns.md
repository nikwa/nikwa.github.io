---
title: "Physics-informed neural networks"
excerpt: "How can physics-informed neural networks be used in a probabilistic setting? <br/><img src='/images/pinn-example.png'>"
collection: portfolio
---

Another way to leverage machine learning models with first principles is using ''physics-informed neural networks'' (PINNs). PINNs are used for solving partial differential equations (PDEs) where the solution of these PDEs is parametrized with a neural network. To enable this, PINNs make use of the flexibility provided by automatic differentiation by enforcing the PDEs at so-called collocation points. We am interested in how PINNs can be used in a probabilistic setting \[[C22, W1](#references)\], with a special focus on dynamical systems.

## References

###### \[C22\] [<SPAN STYLE="font-weight:normal">P. Pilar and N. Wahlström. _Physics-informed neural networks with unknown measurement noise._ Learning for Dynamics \& Control Conference, Oxford, July (2024).</SPAN>](https://proceedings.mlr.press/v242/pilar24a.html)

###### \[W1\] [<SPAN STYLE="font-weight:normal">P. Pilar, M. Heinonen, and N. Wahlström. _Repulsive Ensembles for Uncertainty Estimation in PINNs_ (2025) (working manuscript)
