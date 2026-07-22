---
title: ''
toc: false
image: "profile.jpg"
width: full
---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

{{< hextra/hero-container
  image="profile-circle.png"
  imageClass="hx-block hx-overflow-hidden hx-rounded-full hx-shadow-lg hx-border hx-border-gray-200"
  imageWidth="300"
  imageHeight="300"
  imageTitle="profile"
>}}

<div class="hx:mt-10"></div>

<div class="hx-mt-12 hx-mb-6">
{{< hextra/hero-headline >}}
  Joanna Zou
{{< /hextra/hero-headline >}}
</div>

<div class="hx-mt-6 hx-mb-12">
{{< hextra/hero-subtitle >}}
<p style="color: rgba(1, 107, 230); font-size: 20px;">
  Applied Statistics, Stochastics, and ML
</p>
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx:mt-6"></div>

<div class="hx-mt-6 hx-mb-12">
{{< hextra/hero-subtitle >}}
  My research integrates **machine learning models**, drawing on data from simulations or experiments, with the governing equations of **stochastic dynamical systems** to predict complex phenomena in science and engineering. 
{{< /hextra/hero-subtitle >}}
</div>



<div class="hx:mt-6"></div>


{{< /hextra/hero-container >}}

<div class="hx-mt-6 hx-mb-12">
{{< hextra/hero-subtitle >}}
  My projects are on:
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx:mt-6"></div>


{{< hextra/feature-grid >}}
  {{< hextra/feature-card
    title="Theory"
    subtitle="Leveraging tools from **probability, inference and information theory, stochastic analysis, optimization, and operator theory** to formulate methods with mathematical guarantees."
  >}}
  {{< hextra/feature-card
    title="Algorithms"
    subtitle="Developing tractable algorithms for **variational inference, sampling, active learning, Bayesian filtering, dimension reduction, and uncertainty quantification**, implemented in Python and Julia."
  >}}
  {{< hextra/feature-card
    title="Applications"
    subtitle="Bringing theory into practice in AI-for-science disciplines such as **molecular dynamics, structural dynamics, diffusion models, optimal control, risk analysis, and digital twins**."
  >}}
{{< /hextra/feature-grid >}}


## About 

I am a Postdoctoral Associate at MIT in the [Laboratory for Information & Decision Systems (LIDS)](https://lids.mit.edu/). In May 2026, I completed my PhD in [Computational Science & Engineering](https://cse.mit.edu/) with a minor in Analysis & Probability in the [Uncertainty Quantification Group](https://uqgroup.mit.edu/home) at MIT, advised by Youssef Marzouk. During my PhD, I was a visiting fellow with the [SFB 1294 Collaborative Research Center for Data Assimilation](https://www.sfb1294.de/) at the University of Potsdam, hosted by Han Cheng Lie, and a PhD research intern in the [Combustion Research Facility at Sandia National Laboratories](https://crf.sandia.gov/), hosted by Habib Najm. 

Prior to starting my PhD in 2022, I was a Fulbright pre-doctoral researcher at TU Delft hosted by Eliz-Mari Lourens and Alice Cicirello. Previously, I was a software development associate with the [NHERI Computational Modeling and Simulation Center](https://simcenter.designsafe-ci.org/) and a research intern in the [Advanced Technology & Research team at Arup](https://www.arup.com/en-us/services/specialist-technology-analytics-and-research/). I received my Masters of Science in Structural Engineering from Stanford University, supported by the Stanford School of Engineering Graduate Fellowship, in 2020. I graduated *magna cum laude* with a Bachelors of Science in Civil Engineering and minor in Architecture from Columbia University in 2018. 

With an interdisciplinary background, I am passionate about fundamental research in mathematics and machine learning as well as applied research in a wide range of fields, including AI-driven materials design, climate forecasting, urban sustainability, renewable energy, and decision-making under uncertainty.

### Connect

<center>

{{< icon "mail" >}} **Email**: jjzou (at) mit (dot) edu 
&nbsp;&nbsp;&nbsp;&nbsp; {{< icon "linkedin" >}} [LinkedIn](https://www.linkedin.com/in/joannazou/)
&nbsp;&nbsp;&nbsp;&nbsp; {{< icon "academic-cap" >}} [Google Scholar](https://scholar.google.com/citations?user=stW6M5gAAAAJ&hl=en)
&nbsp;&nbsp;&nbsp;&nbsp; {{< icon "github" >}} [Github](https://github.com/joannajzou/)

</center>




## News

| <div style="width:5px"></div> | <div style="width:100px"></div> |            |
| ----- | ----------- | -----------|
| {{< icon "document-text" >}} | **May 2026** | Our preprint of "Stein kernelized molecular dynamics for active learning of interatomic potentials" is now on ArXiv. |
| {{< icon "microphone" >}} | **Apr 2026** | I defended my thesis, "Goal-Oriented Learning of Stochastic Dynamical Systems", for the PhD in Computational Science & Engineering at MIT.  |
| {{< icon "microphone" >}} | **Mar 2026** | I gave a talk and co-organized two minisymposia, **Advances in MCMC Sampling Methods** and **UQ for Multiscale Modeling in Computational Chemistry**, at the [SIAM Conference for Uncertainty Quantification](https://www.siam.org/conferences-events/siam-conferences/uq26/) in Minneapolis, MN. |
| {{< icon "document-text" >}} | **Mar 2026** | Our preprint of "Goal-oriented learning of stochastic differential equations using error bounds on path-space observables" is now on ArXiv. |
| {{< icon "presentation-chart-line" >}} | **Nov 2025** | I presented a poster on "A goal-oriented loss for learning transition times with machine learning potentials" at the [CoMPASs Workshop](https://icms.ac.uk/activities/workshop/compass-computational-materials-science-and-mathematics-at-the-particle-and-atomistic-scales/) at the International Center for Mathematical Sciences (ICMS) in Edinburgh, UK. |
| {{< icon "microphone" >}} | **May 2025** | I gave a talk and co-organized a minisymposium, **Learning Dynamical Systems and Their Observable Statistics**, at the [SIAM Conference on Applications of Dynamical Systems](https://www.siam.org/conferences-events/past-event-archive/ds25/) in Denver, CO, along with Matthew Levine and Han Cheng Lie. |


<!-- <span style="color:orange">Upcoming!</span> -->

<div class="hx:mb-6">
{{< hextra/hero-button text="Past Announcements" link="news">}}
</div>



## Current Projects

{{< cards cols="2" >}}
{{< card link="projects/soc/" title="Robust Stochastic Optimal Control in Reduced Dimensions" image="projects/cesmix/cesmix0.png" subtitle="Solving stochastic optimal control problems on reduced-dimensional control space" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
{{< card link="projects/dimred/" title="Low-Rank Structure in Drift Functions of SDEs" image="projects/dimred/dimred.png" subtitle="A spectral method to solve for observable-adapted subspaces of Hilbert spaces of drift functions " tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
{{< card link="projects/golearn/" title="Path-Space Approaches to Learning Stochastic Differential Equations" image="projects/golearn/golearn.png" subtitle="Adapting error bounds on path-space observables into variational learning objectives for SDEs" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
{{< card link="projects/skmd/" title="Stein Kernelized Dynamics for Active Learning" image="projects/skmd/skmd.png" subtitle="Adaptively selecting data via particle flows for training energy-based models" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
<!-- {{< card link="projects/cesmix/" title="Mixed-Precision Gaussian Processes" image="projects/cesmix/cesmix0.png" subtitle="Accelerating Gaussian process regression using mixed-precision covariances" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}} -->
{{< /cards >}}



## Past Projects

{{< cards cols="2" >}}
{{< card link="projects/rareevent/" title="Controlled Generative Diffusions for Rare Event Simulation" image="projects/rareevent/diffusion.png" subtitle="Adjoint matching and diffusion modeling for sequential approaches to rare event estimation" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
{{< card link="projects/dpp/" title="Training Set Selection by Determinantal Point Processes" image="projects/dpp/dpp.png" subtitle="A probabilistic approach to D-optimal experimental design" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
<!-- {{< card link="projects/cesmix/" title="Adaptive Importance Sampling in Multifidelity Monte Carlo" image="projects/cesmix/cesmix0.png" subtitle="Importance sampling-based control variates for MFMC" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}} -->
{{< card link="projects/cesmix/" title="Bayesian Methods for Atomistic Modeling of Materials" image="projects/cesmix/cesmix.png" subtitle="Multiscale simulation and uncertainty propagation in computational materials science" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
{{< card link="projects/eigenvalue/" title="Numerical Solutions to Fredholm Integral Eigenvalue Problems" image="projects/eigenvalue/eigvec0.png" subtitle="Nyström and Galerkin projection methods to solving integral eigenvalue problems in KL expansions" tag="" tagColor="orange" method="Crop" options="600x q80 webp">}}
{{< card link="projects/windturbine/" title="Bayesian Filtering for Digital Twins" image="projects/windturbine/windturbine0.png" subtitle="Robust structural health monitoring via Gaussian process latent force models" tag="" tagColor="purple" method="Crop" options="600x q80 webp">}}
{{< card link="projects/seismic/" title="Heteroscedastic Gaussian Process Surrogate Modeling" image="projects/seismic/seismic0.png" subtitle="Surrogate modeling for regional-level seismic simulation" tag="" tagColor="purple" method="Resize" options="600x q80 webp">}}
{{< card link="projects/pbee/" title="High-Performance Computing for Probabilistic Hazard Analysis" image="projects/pbee/pbee.png" subtitle="Risk-informed decision making for natural hazards" tag="" tagColor="orange" method="Resize" options="600x q80 webp">}}
{{< card link="projects/croptype/" title="Image Segmentation for Land Use Classification" image="projects/croptype/croptype0.jpg" subtitle="U-Net classifier of early crop types from satellite imagery" tag="" tagColor="orange" method="Resize" options="600x q80 webp">}}
<!-- {{< card link="projects/mdvibe/" title="Signal Processing for Vibration-Based Activity Monitoring" image="projects/mdvibe/footsteps2.png" subtitle="Selecting signal processing-based features of footstep vibrations for human gait analysis" tag="" tagColor="orange" method="Resize" options="600x q80 webp">}} -->
{{< /cards >}}
   
<br />

<!-- <div class="hx:mb-6">
{{< hextra/hero-button text="Older Projects" link="projects/arch/">}}
</div> -->
