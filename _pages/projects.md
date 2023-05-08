---
layout: archive
title: "Course Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

This page includes some of the projects/term paper explorations that I've worked on, including coursework projects and other side projects.

## Mean-field analysis of the Bose-Hubbard model (PHY665 - Quantum Phases of Matter and Phase Transitions) 
-----
This term paper project explores the quantum phases exhibited by the Bose-Hubbard model in the ground state regime. 

The mean-field theory of the Bose-Hubbard model decouples the self-interaction term in the Hamiltonian, and the mean-field decoupled Hamiltonian is a sum over single-particle Hamiltonians $\hat{H} = \sum_i \hat{h}_i$. The expectation value of the annihilation operator (also the mean-field parameter) acts like the new order parameter $\langle \hat{a} \rangle = \phi$, and the numerical fixed-point iteration method distinguishes the Mott insulator and the Superfluid phases. Further, we also perform a perturbative analysis of the mean-field theory, and we find that the phase boundaries predicted numerically by the fixed-point iteration method and perturbation theory match exactly. The slides for the term paper presentation can be found [here](https://kunal1729verma.github.io/files/PHY665_Term_Paper_Kunal_and_Ritik.pdf).


## Complex system models (IDC621 - Modelling Complex Systems) 
-----
We worked on a variety of complex system models throughout the course, and exploring them using computer simulations via brief term papers. A brief summary and the repositories for the projects are as follows
* [**SIRS Cellular Automata**](https://github.com/kunal1729verma/idc621-modelling_complex_systems/tree/master/SIRS) - the SIRS model is a discrete time lattice model with the time evolution described by a set of "rules", and formally this system is known as a cellular automata. The states of the SIRS cellular automata cycle from Susceptible, Infected, Referactory and back to Susceptible, modelling a disease spread in a population.
* [**Sandpile model**](https://github.com/kunal1729verma/idc621-modelling_complex_systems/tree/master/Sandpile) - the sandpile models are an example of cellular automata exhibiting self-organized criticality i.e. several characteristic features emerged independent of finer details of the system. The sandpile model exhibits self-organized criticality with several observables of the model showing power law distributions.
* [**Kuramoto oscillator chains**](https://github.com/kunal1729verma/idc621-modelling_complex_systems/tree/master/Kuramoto) - the Kuramoto model describes a large set of coupled oscillators which exhibits the property of collective synchronization above a certain level of coupling strength, very similar to the synchronous flashing of a posse of fireflies.<br>

The repository for the term papers can be found [here](https://github.com/kunal1729verma/idc621-modelling_complex_systems).

## Measuring the correlation dimension of strange attractors (IDC402 - Nonlinear Dynamics and Chaos)
-----
In this term paper, I estimated the fractal dimension of two strange attractors, namely the Lorenz system (3D continuous) and the Henon map (2D map). The correlation function $C(\varepsilon)$ is defined as the probability of finding any two points in the attractor distance within some ball of radius $\varepsilon$, and is expected to be related as a power law $C(\varepsilon) \sim \varepsilon^{d_c}$. The repository for the term paper can be found [here](https://github.com/kunal1729verma/idc402-nonlinear_dynamics_and_chaos).

## News Recommender System (IDC410 - Machine Learning) 
-----
In this project, we (my friends [Bhavik](https://github.com/bhavikorange), [Akshay](https://github.com/20akshay00), [Aniket](https://github.com/aniket-sharma-768) and I) attempted to design a news recommender system by scraping off news articles from some popular news websites, and used methods of Natural Language Processing - vectorizing the news corpus and extracting relevant topics using LSA and NER and so on. In order to provide users with recommendations, we gathered analytics by creating user profiles, and calculating an "engagement score" for each read article to recommend the next set of articles. We use a combination of content-based and collaborative-based recommendations to generate the news feed for each user. All the relevant code, including the final API and the report can be found in [this repository](https://github.com/20akshay00/News-Recommender-System).

## Modelling Piezoelectric devices both as transmitters and receivers (PHY312 - Advanced Electronics Lab project)
-----
In this project, we ([Bhavik](https://github.com/bhavikorange) and I) modelled a piezoelectric transducer as a transmitter and a receiver of acoustic pressure signals. By applying an input voltage to the piezoelectric transducer, we can induce stress in the material. This induced stress transmits acoustic pressure waves which travel upwards till they reflect from the rigid top walls and arrive back at the top surface of the transducer. The pressure waves cause the material to deform under stress again, which induces a voltage signal at the top surface of the transducer, and thus it acts as a receiver. The project was carried out in COMSOL Multiphysics. The repository for the project can be found [here](https://github.com/kunal1729verma/phy312-electronics_lab_project).
