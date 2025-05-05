---
title: "Physics-informed generative models"
excerpt: "We are developing physics-informed generative models tailored for scientific applications.<br/><img src='/images/icecube-dm.png'>"
collection: portfolio
---

In recent years, experimental physics has seen increasing usage of ''generative machine learning'' for modeling labor-intensive experiments or computationally expensive simulators. The purpose of these generative models is to act as alternative simulators being more efficient in finding good experimental parameters and also to find hidden patterns in the high-dimensional data explaining the underlying physics. 
	
Even though the data is typically very high-dimensional, physicists are often particularly interested in certain low-dimensional features of this data, e.g. total spectral energy, min-max values and Minkowski functionals. For this purpose, we are developing a physics-informed generative model that can generate realistic high-dimensional samples and at the same time pay extra attention to that the distributions of the real and generated data match particularly well for these low-dimension feature \[[J9](#references)\]. We explore more ways of making generative models more physics-informed and also generalize our model to a conditional generative model \[[W2](#references)\], in order to be a truly attractive alternative physics simulators.

## References

###### \[J9\] [<SPAN STYLE="font-weight:normal">P. Pilar and N. Wahlström. _Probabilistic Matching of Real and Generated Data Statistics in Generative Adversarial Networks_ Transactions on Machine Learning Research (2024).</SPAN>](https://openreview.net/forum?id=o1oetBJuSv)

###### \[W2\] [<SPAN STYLE="font-weight:normal">P. Pilar, C. Glaser and N. Wahlström. _A Surrogate Model for the Generation of Radio Pulses from Neutrinos for IceCube-Gen2_ (2025) (working manuscript)
