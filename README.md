# New [M@TE](https://mate.science/)! model: 
 _we have provided a summary of your model as a starting point for the README, feel free to edit_
## Section 1: Summary of your model   

**Model Submitter:**  

Neng Lu ([0000-0001-9424-2315](https://orcid.org/0000-0001-9424-2315))

**Model Creator(s):**  

- Neng Lu ([0000-0001-9424-2315](https://orcid.org/0000-0001-9424-2315))  
  
**Model slug:**  

`Lu-2026-ALEIB-Coupling` 

(this will be the name of the model repository when created) 

**Model name:**  

_A novel ALE scheme with the internal boundary for coupling tectonic and surface processes in geodynamic models_  

**License:**  

[Creative Commons Attribution 4.0 International]( https://creativecommons.org/licenses/by/4.0/legalcode.txt)

**Model Category:**  

- model published in study   
  
**Model Status:**  

- completed   
  
**Associated Publication title:**  

_[A novel ALE scheme with the internal boundary for coupling tectonic and surface processes in geodynamic models](https://doi.org/10.5194/gmd-19-5723-2026)_ 

**Short description:**  

In this paper, we present a novel coupling framework that integrates the geodynamic codes Underworld 2 with the surface process code Badlands within the ALE-IB scheme. First, we outline the modelling approach and detail the principles underlying the coupling between surface processes and tectonic deformation. Second, we compare the performance of the coupled model built within this framework to that of an Eulerian-based approach, examining differences in structural and dynamic behaviour under varying surface process intensities.

**Abstract:**  

Recent advancements in modelling the deformation of the Earth's crust and upper mantle, coupled with surface processes, have significantly deepened our understanding of how the Earth responds to integrated tectonic and erosional forces, which are intricately linked to climate dynamics. This study presents a novel coupling framework within the Arbitrary Lagrangian–Eulerian with Internal Boundary (ALE-IB) scheme, which integrates the geodynamic codes Underworld 2 with the surface process code Badlands. Our innovative approach addresses the limitations of previous Eulerian-based coupling frameworks by maintaining the integrity of internal interfaces and providing precise surface tracking. This ensures accurate representation of material boundaries and enhances the fidelity of simulations involving complex geological processes. We detail the principles underlying the coupling of surface processes with tectonic deformation, leveraging the strengths of the ALE-IB scheme to model free surfaces and moving boundaries effectively. By comparing our model's performance with an Eulerian-based approach, we highlight key differences in structural and dynamic behaviour under varying surface process intensities. This comparison offers valuable insights into the intricate interactions between surface and deep Earth processes. Our findings contribute to a more comprehensive understanding of geomorphological and tectonic evolution, providing a robust framework for future research in geodynamic and climate-related geological studies.

**Scientific Keywords:**  

- ALE   
- internal boundary   
- coupling   
- surface processes   
  
**Funder(s):**  
- ARC (https://ror.org/05mmh0f86)  
  
## Section 2: your model code, output data  

**No embargo on model contents requested** 

**Include model code:**   

True 

**Model code existing URL/DOI:**   

https://github.com/NengLu/ALEIB_CouplingModeling 

**Model code notes:**   

Models are set up with Python scripts. Models require underworld2 and badlands to be run. 

**Include model output data:**   

True 

**Model output data notes:**   

output is primarily h5 files, ~34.2 GB of data. 

## Section 3: software framework and compute details   
**Software Framework DOI/URL:**  

Found software: _[Underworld2, Badlands](https://doi.org/10.5281/zenodo.15128361)_ 

**Software Repository:**   

https://github.com/underworldcode/underworld2 

**Name of primary software framework:**  

Underworld2, Badlands 

**Software framework authors:**  
-  Romain Beucher ([0000-0003-3891-5444](0000-0003-3891-5444))  
-  Julian Giordani ([0000-0003-4515-9296](0000-0003-4515-9296))  
-  Louis Moresi ([0000-0003-3685-174X](0000-0003-3685-174X))  
-  John Mansour ([0000-0001-5865-1664](0000-0001-5865-1664))  
-  Owen Kaluza ([0000-0001-6303-5671](0000-0001-6303-5671))  
-  Mirko Velic   
-  Rebecca Farrington ([0000-0002-2594-6965](0000-0002-2594-6965))  
-  Steve Quenette ([0000-0002-0368-7341](0000-0002-0368-7341))  
-  Adam Beall ([0000-0002-7182-1864](0000-0002-7182-1864))  
-  Dan Sandiford ([0000-0002-2207-6837](0000-0002-2207-6837))  
-  Luke Mondy ([0000-0001-7779-509X](0000-0001-7779-509X))  
-  Claire Mallard ([0000-0003-2595-2414](0000-0003-2595-2414))  
-  Patrice Rey ([0000-0002-1767-8593](0000-0002-1767-8593))  
-  Guillaume Duclaux ([0000-0002-9512-7252](0000-0002-9512-7252))  
-  Arijit Laik ([0000-0002-3484-7985](0000-0002-3484-7985))  
-  Sara Morón ([0000-0002-1270-4377](0000-0002-1270-4377))  
-  Adam Beall ([0000-0002-7182-1864](0000-0002-7182-1864))  
-  Ben Knight ([0000-0001-7919-2575](0000-0001-7919-2575))  
-  Neng Lu ([0000-0001-9424-2315](0000-0001-9424-2315))  
  
**Software & algorithm keywords:**  

- python   
- finite element   
- particle in cell   
  
## Section 4: web material (for mate.science)   
**Landing page image:**  

Filename: [graphics/Image.png](https://github.com/user-attachments/assets/56d9a3e6-c892-42be-ac0a-0346b91ed279)  
Caption: (a, b) Material, (c, d) viscosity, and (e, f) accumulated plastic strain of the coupling model in ALE-IB and Eulerian scheme (CC-CM2 and CC-CME) at Time=4.5 Ma.  
  
**Animation:**  

Filename: [None]()  
  
**Graphic abstract:**  

Filename: [None]()  
  
**Model setup figure:**  

Filename: [graphics/Image.png](https://github.com/user-attachments/assets/fa25f3c9-81c7-49ba-9bed-a78194afe7b1)  
Caption: Model setup for (a) viscous relaxation of sinusoidal topography, (b) continental collision, (c) strength profile for the models of continental collision.  
Description:  1. Topography relaxation
The loading of the Earth's surface can be described as the initial periodic surface displacement of an isoviscous fluid within the infinite half-space ([Turcotte and Schubert](https://gmd.copernicus.org/articles/19/5191/2026/#bib1.bibx44), [2002](https://gmd.copernicus.org/articles/19/5191/2026/#bib1.bibx44)).

2. Continental collision
A 2D thermo-mechanical model with surface processes to study the integrated influence of tectonics and surface processes on continental collision. The initial configuration consists of a homogeneous crust with a 45° dipping weak zone within the mantle lithosphere at x=640 km, representing a pre-existing subduction zone. The crust is 25 km thick and is overlain by a 40 km-thick sticky-air layer. The tectonic models part is adapted from [Vogt et al.](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx55) ([2018](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx55)) and [Knight et al.](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx24) ([2021](https://gmd.copernicus.org/articles/19/5723/2026/#bib1.bibx24)).

  
