---
title: "Gaussian process latent force models for virtual sensing" # Title of your project
weight: 2 # Order in which to show this project on the home page
external_link: "" # Optional external link instead of modal
resources:
    - src: windturbine0.png
---


#### We show that a Bayesian filtering technique which probabilistically models unknown inputs of a dynamical system can be used to efficiently estimate critical states of in-situ structures, paving a way for improved structural health monitoring and performance-based design of offshore wind turbines.



***References***  

[**J. Zou**, E. Lourens, A. Cicirello. "Virtual sensing of subsoil strain response in monopile-based offshore
wind turbines via Gaussian process latent force models." *Mechanical Systems & Signal Processing.* 200 (110488). 2023.](https://www.sciencedirect.com/science/article/abs/pii/S0888327023003965?via%3Dihub)
&nbsp;

[**J. Zou**, A. Cicirello, A. Iliopoulos, E. Lourens. "Gaussian process latent force models for virtual sensing in a monopile-based
offshore wind turbine." *Proceedings of the European Workshop on Structural Health Monitoring, pp. 290-29.* 2022.](https://link.springer.com/chapter/10.1007/978-3-031-07254-3_29)

***Repository*** 
[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=joannajzou&repo=GPLFM)](https://github.com/joannajzou/GPLFM)


***Challenge.***
Support structures for offshore wind turbines must be designed for efficiency and resiliency in order to meet growing global demand for renewable energy. However, designs must account for the high susceptibility of offshore wind turbines to cyclic (fatigue) damage, due to their widely varying environmental loading conditions over time as well as the potential for resonance effects, which occur when the structure's natural frequencies coincide with the turbine's rotor frequencies. Monitoring fatigue-induced strains is generally infeasible, since critical regions of the support structure lie near the mudline in offshore settings where installation and maintenance of sensors often proves unsuccessful. 


***Solution.***
Virtual sensing is a promising solution for monitoring the progression of fatigue damage in existing offshore wind farms, many of which are approaching the end of their service life, and informing the performance-based design of new offshore wind farms slated for construction over the next several years. Rather than rely on a physical sensor to measure fatigue-induced strains, virtual sensing extrapolates these strains at inaccessible locations of the structure using a limited and indirect set of vibration measurements from accessible locations. This extrapolation is performed using a hybrid model combining a physics-driven model of the structure with a data-driven model of unknown (latent) quantities. 


***Methodology.***
In this work, we propose using a **Gaussian process latent force model (GPFLM)**, a Bayesian filtering technique for joint input-state estimation, to perform the virtual sensing task. In particular, we cast both unknown sources of excitation (the "input") and unknown strains of the structure (the "state") into a joint Gaussian process model, redefining the system dynamics to be dictated by a stochastic differential equation. An augmented state space model encodes covariance relationships between the latent quantities and measured accelerations, allowing for the dynamic structural response to be reconstructed by means of Kalman filtering and smoothing. 


***What's New?***
While the input loading is known to dictate the response behavior of structural systems, previous models for virtual sensing would either neglect unknown inputs or treat them as white noise in the dynamics, leading to suboptimal state estimates. The GPLFM is one of the first approaches to provide an explicit time-varying statistical model of the unknown forces and unaccounted noise which is learned from data. Moreover, this statistical model is a non-parametric representation of latent states, such that the problem of learning covariance relationships between states reduces to the inference of parameters of the GP covariance kernel. 


***Implementation.***
This work is one of the first studies of the performance of the GPLFM for virtual sensing using in-situ vibration data from an operating structure. We use vibration data collected from an offshore wind turbine in the Westermeerwind Park in the Netherlands, consisting of acceleration data at three points along the height of the turbine tower used for data assimilation and strain data along the profile of the monopile foundation used for validation. We demonstrate that the GPLFM leads to accurate reconstruction of strain time histories of the offshore wind turbine in varying operational states with as few as two sensor channels at accessible locations of the structure. Moreover, we find that when model error is explicitly introduced, the error is accommodated by the use of a probabilistic model of the unknown inputs without sacrificing the performance of strain estimation. Our studies indicate that the use of the GPLFM for virtual sensing leads to greater estimation accuracy, robustness to error, and instrumentation efficiency than comparable non-probabilistic approaches. 