---
layout: page
title: Exotic Energy Injection in the Early Universe
permalink: /energy_injection/
usemathjax: true
---

Many extensions of the Standard Model of particle physics predict new particles that are present in the early Universe. These new particles may also include dark matter (DM). These new particles may decay or annihilate into high-energy, electromagnetically interacting Standard Model particles, such as electrons, positrons and photons. Other hypothetical astrophysical objects, such as primordial black holes, are also expected to emit high-energy Standard Model particles. 

As these particles travel across the Universe, they encounter the cosmic microwave background (CMB), hydrogen atoms or free electrons (which cosmologists refer to as 'baryons'), cascading into other, lower energy particles. They also deposit their energy into the CMB or the baryons. This energy deposition could manifest itself as increased **ionization** and **heating** in the baryons, or as the appearance of **low-energy photons** on top of the expected blackbody CMB spectrum. 

*Our goal is to look for extra ionization, heating or low-energy photons that could have originated from such new physics processes.*


## DarkHistory
[Computational methods](/computation/) is extremely important to this. Calculating how high-energy particles cascade into lower energy particles and deposit their energy into baryons can be accomplished with [**DarkHistory**](https://github.com/hongwanliu/DarkHistory) [1, 2, 3]. This code is publicly available and easy to modify. Out of the box, you can specify a DM model with some decay or annihilation rate into some spectrum of electrons and photons, and obtain the ionization, temperature and low-energy photon spectrum as a function of time. This can self-consistently include reionization as well. 


![DarkHistory calculation os ionization and temperature histories, showing self-consistent calculation of reionization and DM effects.](/images/DHv1.jpg)


## Experimental Signatures
Given an exotic source of energy injection, and its predicted increase ionization, heating or low-energy photons, we can now look for experimental signatures of these changes. We have shown how to use the Lyman-$\alpha$ forest---which is sensitive to excess heating in a redshift range of $2 \lesssim z \lesssim 5$---to search for dark matter annihilation and decay [4], as well as [dark photon](/dark_photons/) DM [5, 6, 7]. 


## Bibliography
[1] Hongwan Liu, Gregory W. Ridgway and Tracy R. Slatyer, "DarkHistory: A Code Package for Calculating Modified Cosmic Ionization and Thermal Histories with Dark Matter and other Exotic Energy Injections", PRD 101, 023530 (2020), [arXiv:1904.09296](https://arxiv.org/abs/1904.09296)

[2] Hongwan Liu, Wenzer Qin, Gregory W. Ridgway and Tracy R. Slatyer, "Exotic Energy Injection in the Early Universe I: A Novel Treatment for Low-Energy Electrons and Photons", PRD 108, 043530 (2023), [arXiv:2303.07366](https://arxiv.org/abs/2303.07366)

[3] Hongwan Liu, Wenzer Qin, Gregory W. Ridgway and Tracy R. Slatyer, "Exotic Energy Injection in the Early Universe II: CMB Spectral Distortions and Constraints on Light Dark Matter", PRD 108, 043531 (2023), [arXiv:2303.07370](https://arxiv.org/abs/2303.07370)

[4] Hongwan Liu, Wenzer Qin, Gregory W. Ridgway and Tracy R. Slatyer, "Lyman-$\alpha$ Constraints on Cosmic Heating from Dark Matter Annihilation and Decay", PRD 104, 043514 (2021), [arXiv:2008.01084](https://arxiv.org/abs/2008.01084)

[5] Andrea Caputo, Hongwan Liu, Siddharth Mishra-Sharma and Joshua T. Ruderman, "Dark Photon Oscillations in Our Inhomogeneous Universe", PRL 125, 221303 (2020), [arXiv:2002.05165](https://arxiv.org/abs/2002.05165)

[6] Andrea Caputo, Hongwan Liu, Siddharth Mishra-Sharma and Joshua T. Ruderman, "Modeling Dark Photon Oscillations in Our Inhomogeneous Universe", PRD 102, 103533 (2020), [arXiv:2004.06733](https://arxiv.org/abs/2004.06733)

[7] James S. Bolton, Andrea Caputo, Hongwan Liu and Matteo Viel, "Comparison of Low-Redshift Lyman-$\alpha$ Forest Observations to Hydrodynamical Simulations with Dark Photon Dark Matter", PRL 129, 211102 (2022), [arXiv:2206.13520](https://arxiv.org/abs/2206.13520)