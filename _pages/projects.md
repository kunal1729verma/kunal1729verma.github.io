---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<hr style="text-align:left;margin-left:0;border-top:2px solid #6b7278"> 
This page includes some of the projects/term paper explorations that I've worked on, including coursework projects and other side projects.

## Complex system models (IDC621 - Modelling Complex Systems) 
-----
We worked on a variety of complex system models throughout the course, and exploring them using computer simulations via brief term papers. A brief summary and the repositories for the projects are as follows
* [**SIRS disease spread model**](https://github.com/kunal1729verma/idc621-modelling_complex_systems/tree/master/SIRS) - the SIRS model is a discrete time lattice model with the time evolution described by a set of "rules", and formally this system is known as a cellular automata. The states of the SIRS cellular automata cycle from Susceptible, Infected, Referactory and back to Susceptible, modelling a disease spread in a population.
* [**Sandpile model**](https://github.com/kunal1729verma/idc621-modelling_complex_systems/tree/master/Sandpile) - the sandpile models are an example of cellular automata exhibiting self-organized criticality i.e. several characteristic features emerged independent of finer details of the system. The sandpile model exhibits with several observables of the model showing power law distributions.
* [**Kuramoto oscillator chains**](https://github.com/kunal1729verma/idc621-modelling_complex_systems/tree/master/Kuramoto) - the Kuramoto model describes a large set of coupled oscillators which exhibits the property of collective synchronization above a certain level of coupling strength, very similar to the synchronous flashing of a posse of fireflies.<br>

The repository for the term papers can be found [here](https://github.com/kunal1729verma/idc621-modelling_complex_systems).

## Modelling Piezoelectric Devices as Both Transmitters and Receivers (PHY312 - Advanced Electronics Lab project)
-----
In this project, we modelled a piezoelectric transducer as a transmitter and a receiver of acoustic pressure signals. By applying an input voltage to the piezoelectric transducer, we can induce stress in the material. This induced stress transmits acoustic pressure waves which travel upwards till they reflect from the rigid top walls and arrive back at the top surface of the transducer. The pressure waves cause the material to deform under stress again, which induces a voltage signal at the top surface of the transducer, and thus it acts as a receiver. The project was carried out in COMSOL Multiphysics. The repository for the project can be found [here](https://github.com/kunal1729verma/phy312-electronics_lab_project).


## Measuring the correlation dimension of strange attractors (IDC402 - Nonlinear Dynamics and Chaos)
In this term paper, we estimated the fractal dimension of two strange attractors, namely the Lorenz system (3D continuous) and the Henon map (2D map). The correlation function $C(\varepsilon)$ is defined as the probability of finding any two points in the attractor distance within some ball of radius $\varepsilon$, and is expected to be related as a power law $C(\varepsilon) \sim \varepsilon^{d_c}$. The repository for the term paper can be found [here](https://github.com/kunal1729verma/idc402-nonlinear_dynamics_and_chaos).
