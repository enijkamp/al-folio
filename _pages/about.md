---
layout: about
title: about
permalink: /
description: <a href="#">Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: me.jpg
  address:

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

**About.** I'm a Ph.D. candidate in the [Center for Vision, Cognition, Learning and Autonomy](https://vcla.stat.ucla.edu/){:target="\_blank"} (VCLA) at [UCLA](http://ucla.edu){:target="\_blank"}, advised by Prof. Song-Chun Zhu and Prof. Ying Nian Wu. I've also spent time at [IBM Research](https://www.research.ibm.com/labs/almaden/){:target="\_blank"}, [Google Research](https://research.google/){:target="\_blank"}, and [Salesforce Einstein Research](https://einstein.ai/){:target="\_blank"}. My research is generously supported by the UCLA DYF Fellowship, [XSEDE](https://www.xsede.org/){:target="\_blank"} extreme science and engineering grant, and the [NVIDIA GPU grant](https://developer.nvidia.com/academic_gpu_seeding){:target="\_blank"}.

**Research interests.** Representation Learning, Generative Models, Unsupervised Learning, Energy Based Models, Variational Approximation, Computer Vision, Natural Language Processing.

**Research themes.** The governing theme of my research is to *advance and establish energy-based models:*

(1) EBMs in latent space.
* Latent EBM for semi-supervised classification (To appear).
* Latent EBM as exponential tilted priors (Pang & Nijkamp et al., NeurIPS 2021).

(2) Variations of MCMC-based learning.
* Mixing MCMC. (Preprint 2021, Nijkamp et al.).
* Short-run MCMC for sampling (NeurIPS 2019, Nijkamp et al.) and inference (ECCV 2020, Nijkamp et al.).
* Anatomy MCMC-based learning (AAAI 2020, Nijkamp et al.)
* Mapping of learned EBMs (QAM 2020, Hill & Nijkamp et al.).

(3) Joint training without resorting to MCMC.
* Learning with Flow-based models. (CVPR 2020, Gao & Nijkamp et al.)
* Learning with VAE-based models. (CVPR 2019, Han & Nijkamp et al.) (CVPR 2020, Han & Nijkamp et al.)

**Selected publications.**
<div class="publications">
{% bibliography -f papers -q @*[selected=true]* %}
</div>