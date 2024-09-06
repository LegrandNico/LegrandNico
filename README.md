# :book: About me

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-legrand-9b70342a9/)
[![Mastodon](https://img.shields.io/badge/-MASTODON-%232B90D9?style=for-the-badge&logo=mastodon&logoColor=white)](https://mastodon.social/@nicolegrand)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.fr/citations?user=buFy4tAAAAAJ&hl=fr)

</div>


> I am a researcher in artificial intelligence with a strong interest in probabilistic modelling, causal inference and innovative neural network frameworks, such as predictive coding or self-organizing structures. My main passion is to create algorithms and agents that can perceive, learn, decide and act under environmental uncertainty, with a strong focus on computational efficiency. I am a proficient Python and Rust programmer, and the creator of several open-source packages for physiological signal analysis, psychophysiology experiments, neural networks and computational models of learning and metacognition. I am an experienced data scientist with more than 10 years of practice and have completed several research projects, all involving advanced use of machine learning, cognitive modelling, signal processing, inferential statistics, experimental design or (neuro)physiological recording.

<div align="center">
  
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Julia](https://img.shields.io/badge/-Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)

</div>

---

# :computer: Open source projects

<img src="https://github.com/ilabcode/pyhgf/blob/master/docs/source/images/logo.svg" align="left" alt="pyhgf" height="80" HSPACE=30>

[pyhgf](https://github.com/ilabcode/pyhgf) - A Python library written on top of JAX and RUST to create, manipulate and sample dynamic probabilistic neural networks. It implements by default the generalised Hierarchical Gaussian Filter (see [the method paper](https://arxiv.org/abs/2305.10937)), which is a popular model in computational psychiatry that brings together reinforcement learning and Bayesian inference. The toolbox is designed as a neural network library to work with predictive coding models (which is not possible in standard frameworks like TensorFlow or Pytorch). The models can run forwards or be inverted (all functions comply with JAX transformations, including `grad()`), allowing inference over parameters using e.g. Hamiltonian MCMC. Recently, I have been working on a Rust backend that should push functionalities and performance even further, and eliminate the `DynamicShapes` limiting factor encountered with JAX.

<br clear="left"/>

---

<img src="https://github.com/LegrandNico/systole/blob/master/docs/source/images/logo.svg" align="right" alt="metadpy" height="80" HSPACE=30>

[Systole](https://github.com/embodied-computation-group/systole) is a package centred on processing and visualization of ECG, PPG and respiratory signals. See [here](https://github.com/LegrandNico/systole) for the last versions. It was mainly created to help record PPG and ECG signals using a Python-only API that could interface smoothly with Psychopy. This package is then central for the task developed in Cardioception (see below). It has been extended to an HRV library and supports state-of-the-art analysis with extensive report functionalities, as well as an interactive framework to annotate and correct physiological recordings.

<br clear="right"/>
  
---

<img src="https://github.com/LegrandNico/cardioception/blob/main/docs/source/images/logo.png" align="left" alt="metadpy" height="150" HSPACE=30>

[Cardioception](https://github.com/embodied-computation-group/cardioception) - a psychophysics experiment to measure and analyze cardiac interoceptive beliefs ([the method paper](https://www.sciencedirect.com/science/article/pii/S0301051121002325)). See [here](https://github.com/LegrandNico/cardioception) for the last versions. The task uses Systole for recording and metadpy to estimate metacognitive parameters. The package also provides extensive resources to analyse the data produced by the tasks, including Jupyter notebooks and scripts to fit Bayesian psychometric models automatically.

<br clear="left"/>

---

<img src="https://github.com/LegrandNico/metadpy/raw/master/docs/source/images/logo.png" align="right" alt="metadpy" height="150" HSPACE=30>

[metadPy](https://github.com/embodied-computation-group/metadpy) - a package to compute a variety of metacognitive efficiency parameters from trial-level confidence ratings (SDT, meta-*d* using MLE and Bayesian methods). This is mainly a Python adaptation of the [JAGS version](https://github.com/metacoglab/HMeta-d) of the hierarchical meta-d' model. The package is written on top of Pytensor and PyMC for the Bayesian part and uses Numba for the MLE part. It is designed to interface smoothly with Python and should help extract various metacognitive parameters from multi-participant data frames using a single method call. See [here](https://github.com/LegrandNico/metadpy) for the last versions.
