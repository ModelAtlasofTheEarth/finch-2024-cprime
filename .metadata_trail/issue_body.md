### -> submitter ORCID (or name)

https://orcid.org/0000-0001-9699-2769

### -> slug

finch-2024-cprime

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.1016/j.jsg.2020.104091

### -> model creators

0000-0001-9699-2769
0000-0002-6469-3526
Steinbach, Florian 
0000-0003-4598-8385
0000-0002-6148-2600
0000-0002-1317-6289
0000-0002-8639-3890
0000-0001-5828-8711

### -> title

_No response_

### -> description

This model simulates the development of C' shear bands in ductile shear zones. The model begins with an equigranular texture of three phases: a strong phase (e.g., feldspar) an intermediate-strength phase (e.g., quartz) and an anisotropic weak phase (e.g., mica). Dextral shearing stretches and rotates the microstructure, forming S-C fabric, asymmetric folds and C' shear bands.

### -> abstract

_No response_

### -> scientific keywords

_No response_

### -> funder

https://ror.org/012kf4317
https://ror.org/05r0vyz12, RYC2018-026335-I

### -> model embargo?

_No response_

### -> include model code ?

- [X] yes

### -> model code/inputs DOI

_No response_

### -> model code/inputs notes

The starting microstructure for the model is an .Elle file that can be viewed and edited in notepad or similar. The microstructure can be viewed with the showelle program. To run the simulation the program Elle can be downloaded from elle.ws.

### -> include model output data?

- [X] yes

### -> data creators

_No response_

### -> model output data DOI

_No response_

### -> model output data notes

Output data consists of 900 files that are 21 Mb each and an avi movie that is 80 Mb

### -> model output data size

20 Gb

### -> software framework DOI/URI

https://elle.ws/

### -> software framework source repository

https://sourceforge.net/p/elle/git/ci/master/tree/

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Elle Numerical Simulation Platform

### -> software framework authors

0000-0002-6469-3526
0000-0001-5828-8711
0000-0002-0954-6072
0000-0001-9699-2769
0000-0001-8707-8537
0000-0002-1317-6289
0000-0003-4598-8385
0000-0003-3762-1655
0000-0002-0375-7311
0000-0002-2276-2626
0000-0002-3152-9105
0000-0002-6148-2600
0000-0001-7723-8170
0000-0002-3790-1385
0009-0000-4868-3152

### -> software & algorithm keywords

VPFFT, Elle

### -> computer URI/DOI

_No response_

### -> add landing page image and caption

Stages of microstructural development in a model with 15% weak phase (black) and a medium phase strength contrast. (a) Starting microstructure, (b) stage 1: grain elongation and rotation. Note the distribution of maximum strain rate (red arrows) localised to tips of WP grains that are parallel to the C plane, (c) stage 2: S-C fabric development. Stress is highest in the IP+SP adjacent to high strain rate layers of interconnected WP (red and orange arrows). (d) stage 3: shear band development and strain partitioning. Maximum stress in the model is in the gap in the shear band (red arrow). Green arrows highlight areas that have been asymmetrically folded (c.f. Fig. 1a). The first column shows the grain microstructure, the second column shows the normalised von Mises strain rate and the third column shows the von Mises stress. Images in the same row correspond to the same model and step.
![Fig  3](https://github.com/user-attachments/assets/380a520e-8e72-4fb9-8ba8-422368e5139d)


### -> add an animation (if relevant)

_No response_

### -> add a graphic abstract figure (if relevant)

![Fig  5](https://github.com/user-attachments/assets/ced9599e-7a7d-4275-90b6-206aa72b6dd9)
The formation of C' shear bands by the rotation of a C plane forwards due to high strain rate in the shear band and high stress at the tip of the shear band. (a) Discontinuous shear band with section parallel to the SZB at high strain rate (red arrow) and high stress in the IP+SP region at the end of the shear band (orange arrow). (b) A low strain rate section in the shear band is bracketed on either side by high strain rate sections (red arrows) and begins to rotate forwards. (c) C' shear band forms in low strain rate section (red dashed line). (d) Strain rate reduces in the shear band and the C' shear band has rotated back into parallelism with the SZB and C planes. The first column shows the grain microstructure, the second column shows the normalised von Mises strain rate and the third column shows the von Mises stress. Model shown contains 15% weak phase and a high phase strength contrast. Images in the same row correspond to the same model and step.

### -> add a model setup figure (if relevant)

![Fig 2](https://github.com/user-attachments/assets/640818b2-adbd-421b-839a-3a0a5fa8ad57)
Basic process of microstructure simulation. (a) The starting microstructure consists of three grain types that undergo one increment of γ = 0.02 dextral shear. (b) The microstructure is deformed with wrapping boundaries. (c) The microstructure is repositioned back to a square before the next increment of strain. (d) Zoom in of (a) showing the three flynn (grain) types: strong phase (SP), intermediate-strength phase (IP), and weak phase (WP). (e) Zoom-in of (d) showing that flynn grain boundaries are defined by double (blue) and triple (red) bnodes joined by straight lines. An additional grid of unconnected nodes (unodes, black) is overlain on flynns and stores state variables and flynn properties.

### -> add a description of your model setup

A three-phase microstructure was used with 15% weak phase (WP), 42.5% intermediate-strength phase (IP) and 42.5% strong phase (SP). The starting model was square and defined by 2,748 equant grains with a random distribution of the three phases. Velocity boundary conditions with constant strain rate were applied with top-to-the-right (dextral) simple shear in increments of Δγ = 0.02, up to a finite shear strain of γ=18 in 900 steps. After each deformation step, the model was repositioned to the initial square unit cell and grain properties mapped back on to the grid before the next deformation step. A power-law viscous rheology  was employed with n = 3.
Each phase was associated with a mineral model that specified the slip systems and their effective strength or resistance to shear. The mineral models employed attempted to broadly approximate the most important features of mica (WP), quartz (IP), and feldspar (SP) in order to more closely correspond to previous experimental work. To model the WP we used a mineral model with hexagonal symmetry and three slip systems (basal, prismatic, and pyramidal) because, although mica is monoclinic, it is pseudohexagonal and its most important mechanical feature is an easy glide plane since shear in mica is easier parallel to the basal plane than in any other direction. Accordingly we set  the basal plane of the WP to one tenth of the non-basal WP planes, producing a mechanically anisotropic WP. Feldspar is also pseudohexagonal, so we employed a hexagonal mineral model for the SP, but with all slip systems at the same effective strength. For the IP we used the crystal model of quartz with four slip systems (basal, prismatic, pyramidal <a> and pyramidal <c+a>) and gave the effective strength of all four slip systems the same value, making the IP effectively mechanically isotropic. The IP was 25x stronger than the WP basal plane and the SP was 2x stronger than the IP.

### Please provide any feedback on the model submission process?

_No response_