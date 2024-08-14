---
layout: page
title: Exotic Energy Injection in the Early Universe
permalink: /research/energy_injection/
usemathjax: true
---
<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  }
};
</script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js">
</script>


>*New physics processes can inject extra ionization, heating or low-energy photons, leaving striking experimental signatures in cosmological datasets.*
{: style="font-size: 200%; color:#C90505; text-align:left; font-family:Times New Roman"}


Many extensions of the Standard Model of particle physics predict new particles that are present in the early Universe. These new particles may also include dark matter (DM). They may decay or annihilate into high-energy, electromagnetically interacting Standard Model particles, such as electrons, positrons and photons. Other hypothetical astrophysical objects, such as primordial black holes, are also expected to emit high-energy Standard Model particles. 


As these particles travel across the Universe, they encounter the cosmic microwave background (CMB), hydrogen atoms or free electrons (which cosmologists refer to as 'baryons'), cascading into other, lower energy particles. They also deposit their energy into the CMB or the baryons. This energy deposition could manifest itself as increased ionization and heating in the baryons, or as the appearance of low-energy photons on top of the expected blackbody CMB spectrum. 

[Computational methods](/research/computation/) are extremely important to predicting this signal. Calculating how high-energy particles cascade into lower energy particles and deposit their energy into baryons can be accomplished with [DarkHistory](https://github.com/hongwanliu/DarkHistory) [[1--3](#bib_1)]. This code is publicly available and easy to modify. 



![DarkHistory calculation os ionization and temperature histories, showing self-consistent calculation of reionization and DM effects.](/images/DHv1.jpg)
Figure 1. *DarkHistory calculation of the ionization and temperature histories of our Universe, including reionization and dark matter energy injection effects self-consistently.*
{: style="font-size: 90%; text-align: left;"}



Given an exotic source of energy injection, and its predicted contribution to ionization, heating or low-energy photons, we can now look for experimental signatures of these changes. Observations of the Lyman-$\alpha$ forest---which is sensitive to excess heating in a redshift range of $2 \lesssim z \lesssim 5$---can be used to search for excess heating from dark matter annihilation and decay [[4](#bib_4)], as well as [dark photon](/research/dark_photons/) DM converting into low-energy photons that subsequently heat baryons [[5--7](#bib_5)]. 

![Strong constraints on ultralight dark photon dark matter from Lyman-alpha.](/images/lyman_DPDM.jpg){: width="70%"}
{: style="text-align: center;"}
Figure 2. *Strong constraints on ultralight dark photon dark matter from Lyman-$\alpha$ data, which is highly sensitive to excess heating arising from dark photon dark matter converting into low-energy photons that are subsequently absorbed.*
{: style="font-size: 90%; text-align: left;"}

Ionization, heating and low-energy photons can also leave a significant imprint on the [21-cm signal](/research/21cm/), an up-and-coming cosmological probe that will soon teach us a lot about the cosmic dark ages. The 21-cm global signal is extraordinarily sensitive to DM decay, and has the potential to discover DM decaying with lifetimes that are currently one or two orders of magnitude too small to detect [[8](#bib_8)]. DM processes can also have a significant impact on star formation [[9](#bib_9)], which impacts both the 21-cm global signal and power spectrum. 

![Strong constraints on dark matter decay from 21-cm global signal.](/images/21cm_DM.jpg){: width="70%"}
{: style="text-align: center;"}
Figure 3. *Limits on dark matter decay from the 21-cm global signal measured by EDGES, under various assumptions. Any future 21-cm global signal measurement near the $\Lambda$CDM expectation will likely improve our sensitivity to dark matter decay lifetime by two orders of magnitude.*
{: style="font-size: 90%; text-align: left;"}

## Bibliography
<a name='bib_1'></a>
[1] Hongwan Liu, Gregory W. Ridgway and Tracy R. Slatyer, "DarkHistory: A Code Package for Calculating Modified Cosmic Ionization and Thermal Histories with Dark Matter and other Exotic Energy Injections", PRD 101, 023530 (2020), [arXiv:1904.09296](https://arxiv.org/abs/1904.09296)
{: style="font-size: 80%;"}

<a name='bib_2'></a>
[2] Hongwan Liu, Wenzer Qin, Gregory W. Ridgway and Tracy R. Slatyer, "Exotic Energy Injection in the Early Universe I: A Novel Treatment for Low-Energy Electrons and Photons", PRD 108, 043530 (2023), [arXiv:2303.07366](https://arxiv.org/abs/2303.07366)
{: style="font-size: 80%;"}

<a name='bib_3'></a>
[3] Hongwan Liu, Wenzer Qin, Gregory W. Ridgway and Tracy R. Slatyer, "Exotic Energy Injection in the Early Universe II: CMB Spectral Distortions and Constraints on Light Dark Matter", PRD 108, 043531 (2023), [arXiv:2303.07370](https://arxiv.org/abs/2303.07370)
{: style="font-size: 80%;"}

<a name='bib_4'></a>
[4] Hongwan Liu, Wenzer Qin, Gregory W. Ridgway and Tracy R. Slatyer, "Lyman-$\alpha$ Constraints on Cosmic Heating from Dark Matter Annihilation and Decay", PRD 104, 043514 (2021), [arXiv:2008.01084](https://arxiv.org/abs/2008.01084)
{: style="font-size: 80%;"}

<a name='bib_5'></a>
[5] Andrea Caputo, Hongwan Liu, Siddharth Mishra-Sharma and Joshua T. Ruderman, "Dark Photon Oscillations in Our Inhomogeneous Universe", PRL 125, 221303 (2020), [arXiv:2002.05165](https://arxiv.org/abs/2002.05165)
{: style="font-size: 80%;"}

<a name='bib_6'></a>
[6] Andrea Caputo, Hongwan Liu, Siddharth Mishra-Sharma and Joshua T. Ruderman, "Modeling Dark Photon Oscillations in Our Inhomogeneous Universe", PRD 102, 103533 (2020), [arXiv:2004.06733](https://arxiv.org/abs/2004.06733)
{: style="font-size: 80%;"}

<a name='bib_7'></a>
[7] James S. Bolton, Andrea Caputo, Hongwan Liu and Matteo Viel, "Comparison of Low-Redshift Lyman-$\alpha$ Forest Observations to Hydrodynamical Simulations with Dark Photon Dark Matter", PRL 129, 211102 (2022), [arXiv:2206.13520](https://arxiv.org/abs/2206.13520)
{: style="font-size: 80%;"}

<a name='bib_8'></a>
[8] Hongwan Liu and Tracy Slatyer, "Implications of a 21-cm Signal for Dark Matter Annihilation and Decay", PRD 98, 023501 (2018), [arXiv:1803.09739](https://arxiv.org/abs/1803.09739)
{: style="font-size: 80%;"}

<a name='bib_9'></a>
[9] Wenzer Qin, Julian Muñoz, Hongwan Liu and Tracy Slatyer, "Birth of the First Stars Amidst Decaying and Annihilating Dark Matter", [arXiv:2308.12992](https://arxiv.org/abs/2308.12992)
{: style="font-size: 80%;"}
