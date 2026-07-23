### -> submitter ORCID (or name)

https://orcid.org/0000-0001-9424-2315

### -> slug

Lu-2026-ALEIB-Coupling 

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.5194/gmd-19-5723-2026

### -> model creators

https://orcid.org/0000-0001-9424-2315

### -> title

A novel ALE scheme with the internal boundary for coupling tectonic and surface processes in geodynamic models

### -> description

In this paper, we present a novel coupling framework that integrates the geodynamic codes Underworld 2 with the surface process code Badlands within the ALE-IB scheme. First, we outline the modelling approach and detail the principles underlying the coupling between surface processes and tectonic deformation. Second, we compare the performance of the coupled model built within this framework to that of an Eulerian-based approach, examining differences in structural and dynamic behaviour under varying surface process intensities.

### -> abstract

Recent advancements in modelling the deformation of the Earth's crust and upper mantle, coupled with surface processes, have significantly deepened our understanding of how the Earth responds to integrated tectonic and erosional forces, which are intricately linked to climate dynamics. This study presents a novel coupling framework within the Arbitrary Lagrangian–Eulerian with Internal Boundary (ALE-IB) scheme, which integrates the geodynamic codes Underworld 2 with the surface process code Badlands. Our innovative approach addresses the limitations of previous Eulerian-based coupling frameworks by maintaining the integrity of internal interfaces and providing precise surface tracking. This ensures accurate representation of material boundaries and enhances the fidelity of simulations involving complex geological processes. We detail the principles underlying the coupling of surface processes with tectonic deformation, leveraging the strengths of the ALE-IB scheme to model free surfaces and moving boundaries effectively. By comparing our model's performance with an Eulerian-based approach, we highlight key differences in structural and dynamic behaviour under varying surface process intensities. This comparison offers valuable insights into the intricate interactions between surface and deep Earth processes. Our findings contribute to a more comprehensive understanding of geomorphological and tectonic evolution, providing a robust framework for future research in geodynamic and climate-related geological studies.

### -> scientific keywords

ALE, internal boundary, coupling, surface processes

### -> funder

https://ror.org/05mmh0f86, DP240102450

### -> model embargo?

_No response_

### -> include model code ?

- [x] yes

### -> model code/inputs DOI

https://github.com/NengLu/ALEIB_CouplingModeling

### -> model code/inputs notes

Models are set up with Python scripts. Models require underworld2 and badlands to be run.

### -> include model output data?

- [x] yes

### -> data creators

https://orcid.org/0000-0001-9424-2315

### -> model output data DOI

_No response_

### -> model output data notes

output is primarily h5 files, ~34.2 GB of data.

### -> model output data size

~34.2 GB

### -> software framework DOI/URI

https://zenodo.org/records/15128361

### -> software framework source repository

https://github.com/underworldcode/underworld2

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Underworld2, Badlands

### -> software framework authors

_No response_

### -> software & algorithm keywords

python, finite element, particle in cell

### -> computer URI/DOI

https://nci.org.au/

### -> add landing page image and caption

<img width="3966" height="1994" alt="Image" src="https://github.com/user-attachments/assets/56d9a3e6-c892-42be-ac0a-0346b91ed279" />
(a, b) Material, (c, d) viscosity, and (e, f) accumulated plastic strain of the coupling model in ALE-IB and Eulerian scheme (CC-CM2 and CC-CME) at Time=4.5 Ma.

### -> add an animation (if relevant)

_No response_

### -> add a graphic abstract figure (if relevant)

_No response_

### -> add a model setup figure (if relevant)

<img width="2618" height="1720" alt="Image" src="https://github.com/user-attachments/assets/fa25f3c9-81c7-49ba-9bed-a78194afe7b1" />
Model setup for (a) viscous relaxation of sinusoidal topography, (b) continental collision, (c) strength profile for the models of continental collision.

### -> add a description of your model setup

1. Topography relaxation
The loading of the Earth's surface can be described as the initial periodic surface displacement of an isoviscous fluid within the infinite half-space ([Turcotte and Schubert](https://gmd.copernicus.org/articles/19/5191/2026/#bib1.bibx44), [2002](https://gmd.copernicus.org/articles/19/5191/2026/#bib1.bibx44)).

2. Continental collision
A 2D thermo-mechanical model with surface processes to study the integrated influence of tectonics and surface processes on continental collision. The initial configuration consists of a homogeneous crust with a 45° dipping weak zone within the mantle lithosphere at x=640 km, representing a pre-existing subduction zone. The crust is 25 km thick and is overlain by a 40 km-thick sticky-air layer. The tectonic models part is adapted from [Vogt et al.](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx55) ([2018](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx55)) and [Knight et al.](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx24) ([2021](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx24)).

### Please provide any feedback on the model submission process?

_No response_