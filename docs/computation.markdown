---
layout: page
title: Computational Methods
permalink: /research/computation/
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

>*Progress in artificial intelligence has given rise to many new and powerful computational and data analysis techniques. These will become increasingly important in cosmology and high-energy physics research.*
{: style="font-size: 200%; color:#C90505; text-align:left; font-family:Times New Roman"}

The impact of new physics on observables is typically complicated, and requires significant computational effort to deduce. New physics signals can also be difficult to disentangle from data, and often require careful numerical and statistical analyses to detect. Recent developments in artificial intelligence and associated advances in numerical computation have also significantly expanded what is possible on this front. 



[DarkHistory](https://github.com/hongwanliu/DarkHistory) [[1,2](#bib_1)] is an open-source Python code written to calculate the impact of exotic energy injection on the ionization history, temperature history and low-energy photon spectrum of our cosmos, with the aim of detecting such signatures in experimental measurements such as the CMB energy spectrum, [21-cm signal](/research/21cm) and the Lyman-$\alpha$ forest. It has been extensively used in the literature to study such signatures sourced by particle dark matter, primordial black holes and cosmic strings. 

The tremendous amount of data collected by modern telescopes such as Gaia provides us with unprecedented insight into our Milky Way galaxy and the dark matter halo that surrounds it. Early data from Gaia mostly provided only 5D information (location in the galaxy, and velocity across the sky, but not a star's radial velocity, i.e. speed toward/away from us), making it challenging to study the kinematics of stellar populations in our galaxy. While it is impossible to predict the motion of individual stars, machine learning can be used to provide a best guess for the radial velocity, and assign an uncertainty to this guess. This makes searches for extended substructure in the galaxy possible, even with incomplete information [[3,4](#bib_3)]. 

![Machine learning techniques can be used to recover kinematic substructure in Gaia data from stars that have incomplete kinematic information. Stars belonging to Gaia-Sausage-Enceladus possessing large galactocentric radial velocities can be identified accurately even with only 5D information.](/images/ML_RV.jpg)
{: style="text-align: center"}
Figure 1. *Machine learning techniques can be used to recover kinematic substructure in Gaia data from stars that have incomplete kinematic information. Stars belonging to Gaia-Sausage-Enceladus possessing large galactocentric radial velocities can be identified accurately even with only 5D information.*
{: style="font-size: 90%; text-align: left;"}

Autodifferentiation and optimized compilation of code for machine learning applications are changing the way physicists write code. These tools enable very fast computation of all kinds of numerical methods, and allow for efficient sampling of probability distributions. Upcoming work will show how to use such techniques to greatly improve calculations performed in the modeling of Big Bang Nucleosynthesis and recombination. 

## Bibliography
<a name='bib_1'></a>
[1] Hongwan Liu, Gregory W. Ridgway and Tracy R. Slatyer, "DarkHistory: A Code Package for Calculating Modified Cosmic Ionization and Thermal Histories with Dark Matter and other Exotic Energy Injections", PRD 101, 023530 (2020), [arXiv:1904.09296](https://arxiv.org/abs/1904.09296)
{: style="font-size: 80%;"}

<a name='bib_2'></a>
[2] Hongwan Liu, Wenzer Qin, Gregory W. Ridgway and Tracy R. Slatyer, "Exotic Energy Injection in the Early Universe I: A Novel Treatment for Low-Energy Electrons and Photons", PRD 108, 043530 (2023), [arXiv:2303.07366](https://arxiv.org/abs/2303.07366)
{: style="font-size: 80%;"}

<a name='bib_3'></a>
[3] Adriana Dropulic, Bryan Ostdiek, Laura J. Chang, Hongwan Liu, Timothy Cohen and Mariangela Lisanti, "Machine Learning the 6th Dimension: Stellar Radial Velocities from 5D Phase-Space Correlations", ApJL 915, L14 (2021), [arXiv:2103.14039](https://arxiv.org/abs/2103.14039) 
{: style="font-size: 80%;"}

<a name='bib_4'></a>
[4] Adriana Dropulic, Hongwan Liu, Bryan Ostdiek and Mariangela Lisanti, "Revealing the Milky Way's Most Recent Major Merger with a Gaia EDR3 Catalog of Machine-Learned Line-of-Sight Velocities", MNRAS 512, 1633-1645 (2023), [arXiv:2205.12278](https://arxiv.org/abs/2205.12278)
{: style="font-size: 80%;"}