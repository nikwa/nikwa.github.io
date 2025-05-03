---
title: "Constrained Gaussian processes"
excerpt: "How can prior physical knowledge be incorporated into data-driven Gaussian process models?<br/><img src='/images/constrained-gp.jpg'>"
collection: portfolio
---

Probabilistic models offer a powerful way to encode and describe prior knowledge. One such probabilistic model is the Gaussian process (GP). I am interested in how prior physical knowledge can be incorporated into this data-driven model by deploying constrained GPs. Such physical knowledge can be in the form of partial differential equations such as, for example, [Maxwell's equations for magnetic fields](https://www.youtube.com/watch?v=enlMiUqPVJo) \[[J5](#references)\] or equilibrium constraints for strain fields \[[J6](#references)\]. We have earlier produced results on how linear constraints can be handled \[[C16](#references)\] and more recently showed how to generalize this to one instance of nonlinear constraints \[[J8](#references)\].
	
Further possible development of this project is to not only improve the performance of the GP model by enforcing the constraints, but also discover the constraints directly from data and by that enable new scientific insights. Due to its probabilistic setting, we believe that the GP is a great model for doing this inference and at the same time taking the uncertainties into account regarding the underlying process as well as the data.

## References

###### \[J8\] [<SPAN STYLE="font-weight:normal">P. Pilar, C. Jidling, T. B. Schön, and N. Wahlström. _Incorporating sum constraints into multitask Gaussian processes_ Transactions on Machine Learning Research (2022).</SPAN>](https://openreview.net/forum?id=gzu4ZbBY7S)

###### \[J6\] [<SPAN STYLE="font-weight:normal">C. Jidling, J. Hendriks, N. Wahlström, A. Gregg, T. B. Schön, C. Wensrich, and A. Wills. _Probabilistic modelling and reconstruction of strain_ Nuclear Instruments and Methods in Physics Research Section B: Beam Interactions with Materials and Atoms (2018).</SPAN>](https://arxiv.org/abs/1802.03636)

###### \[J5\] [<SPAN STYLE="font-weight:normal">A. Solin, M. Kok, N. Wahlström, T. B. Schön, and S. Särkkä. _Modeling and interpolation of the ambient magnetic field by Gaussian processes_ IEEE Transactions on Robotics (2018).</SPAN>](https://arxiv.org/abs/1509.04634)

###### \[C16\] [<SPAN STYLE="font-weight:normal">C. Jidling, N. Wahlström, A. Wills, and T. B. Schön. _Linearly constrained Gaussian processes_ The Annual Conference on Neural Information Processing Systems, NIPS (2017).</SPAN>](https://proceedings.neurips.cc/paper_files/paper/2017/hash/71ad16ad2c4d81f348082ff6c4b20768-Abstract.html)

###### \[C7\] [<SPAN STYLE="font-weight:normal">N. Wahlström, M. Kok, T.B. Schön, and F. Gustafsson. _Modeling Magnetic Fields using Gaussian Processes_ The 38th International Conference on Acoustics, Speech and Signal Processing, ICASSP (2013).</SPAN>](http://urn.kb.se/resolve?urn=urn:nbn:se:liu:diva-88966)

