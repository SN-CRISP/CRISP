## Welcome to CRISP

CRISP is a multi-faceted project to study extinction towards supernovae (SNe) and their environments though a variety of observational techniques including photometry, integral field spectroscopy and polarimetry of both SNe and their hosts, as well as machine learning tools and radiative transfer modeling.

<p align="center">
<img src="crisp_logo_cut.jpg" alt="alt text" width=300 height=200>
</p>


## Team and collaborators

Alessandro Razza (U.Chile)<br/>
Ana Mourão (CENTRA-IST)<br/>
Ana Paulina-Afonso (CENTRA-IST)<br/>
Antonia Morales-Garaffolo (U.Cádiz)<br/>
Alberto Krone-Martins (U.Cal-Irvine)<br/>
Beatriz Pereira (CENTRA-IST)<br/>
Claudia Gutiérrez (U.Turku)<br/>
Francisco Förster (U.Chile)<br/>
João Duarte (CENTRA-IST)<br/>
João Silvestre (CENTRA-IST)<br/>
Joe Anderson (ESO)<br/>
Lluis Galbany (U.Granada)<br/>
Marko Stalevski (O.Belgrade)<br/>
Majda Smole (O.Belgrade)<br/>
Pedro Garcia (CENTRA-FCUL)<br/>
Santiago González-Gaitán (CENTRA-IST)<br/>
Thomas de Jaeger (U.Hawaii)<br/>

## Projects


- **ARGAS: Artifically Redshifting of Galaxies (PI: A. Paulina-Afonso)**: <br/>
Recent studies have shown that type Ia supernova distance estimation improves when using an additional term related to the host galaxy mass. However, the bias and systematics of using a limited set of broad-band filters across a large redhift range has never been evaluated. With extensive simulations of nearby integral field spectroscopy (IFS) galaxies set at high redshifts, we study here the impact of effects like dimming, scaling and SED fitting in current and future SN surveys.
![Image](ARGAS.jpg)

- **Impact of varying colour-luminosity relation in type Ia supernova cosmology (PI: T. de Jaeger, S. González-Gaitán)**:<br/>
Type Ia SN cosmology has been essential in determining the accelerated expansion of the universe. However, the standardization of their luminosity to measure distances relies on a color-luminosity calibration that generally assumes a constant factor throughout the SN Ia population. We investigate in this project the effect of letting this parameter vary. [Paper](https://ui.adsabs.harvard.edu/abs/2020arXiv200913230G/abstract) submitted.
<p align="center">
<img src="beta_color_value.jpg" alt="alt text" width=300 height=300>
</p>

- **Dust attenuation slopes of DES galaxies (PI: J. Duarte)**:<br/>
We are obtaining for the first time a set of dust attenuation slopes for a cosmological sample of SNe Ia from their host galaxies with broad-band photometry from the Dark Energy Survey ([DES](https://www.darkenergysurvey.org/)) complemented with available GALEX UV photometry. We use the SED fitter [prospector](https://prospect.readthedocs.io/en/latest/) and [FSPS](https://dfm.io/python-fsps/current/) population synthesis code. The method is tested with simulations.
<p align="center">
<img src="prosp.jpg" alt="alt text" width=250 height=250>
</p>

- **Dust attenuation slope maps of AMUSING galaxies (PI: A. Razza)**:<br/>
We will obtain maps of dust attenuation slopes across nearby galaxies observed with Integral Fiel Spectroscopy (IFS) from the [AMUSING](https://amusing-muse.github.io/) survey. Spectra are complemented with optical, UV and NIR broad-band photometry. The method uses the SED fitter [prospector](https://prospect.readthedocs.io/en/latest/) and [FSPS](https://dfm.io/python-fsps/current/) population synthesis and is being tested with large simulations.


- **Galaxy spatial field reconstruction with INLA (PI: S. González-Gaitán)**::<br/>
The spatial correlations of astrophysical quantities are normally poorly taken into account. As part of the [COIN](https://cosmostatistics-initiative.org/) collaboration, we use here the Integrated Nested Laplace Approximation ([INLA](https://www.r-inla.org/)) machinery to obtain meaningful spatial reconstructions of IFS galaxy properties. The algorithm is very powerful when there is sparsity of data. [Paper](https://ui.adsabs.harvard.edu/abs/2019MNRAS.482.3880G/abstract) published.   

![Image](INLA.jpg)

- **1.5D SED spatial fitting (PI: P. Garcia)**:
The next step of the INLA spatial fitting applied to galaxy IFS is to simulatenously fit the wavelength and the spatial dimension. In a first 1.5D approach, we iteratively fit the SED at each spaxel with [prospector](https://prospect.readthedocs.io/en/latest/) while the spatial part is done with [INLA](https://www.r-inla.org/). 

- **Optimization of radiative transfer codes (PI: M. Smole)**:
Monte Carlo radiative transfer (MCRT) codes like [SKIRT](https://skirt.ugent.be/root/_landing.html) simulate the observed distribution of light as a function of wavelength given an initial geometry and dust composition; but this is computationally expensive. We are using the [INLA](https://www.r-inla.org/) methodology to boost MCRT modeling of Active Galactic Nuclei (AGN) and galaxies requiring less initial photons and less compuational time.

- **Pilot project of polarimetric studies towards galaxies: the case of Circinus (PI: M. Stalevski, S. González-Gaitán)**:<br/>
Imaging polarimetry of the nearby Circinus galaxy, host of an Active Galactic Nucleus (AGN), taken with FORS2-VLT in multiple optical bands allows the study of the geometry and dust characteristics of the central object and its galaxy. 

<p align="center">
<img src="Circinus.jpg" alt="alt text" width=300 height=250>
</p>

- **Polarimetric studies towards galaxies (PI: J. Silvestre)**:<br/>
The first statistical study of multi-band imaging polarimetry with optical data from FORS2-VLT and CAFOS-CAHA will deliver nearby galaxy maps of various physical characteristics like dust and magnetic field alignment. The data will be compared with Monte Carlo radiative transfer simulations with the code [SKIRT](https://skirt.ugent.be/root/_landing.html).

<p align="center">
<img src="galpol.jpg" alt="alt text" width=500 height=230>
</p>

- **Instrumental field polarization of FORS2-VLT (PI: S. González-Gaitán, A Mourão)**:<br/>
Extended imaging polarization studies requires a full characterization of the instrument which is known to produce spurious polarization patterns. We study the instrumental field polarization of the FORS2 instrument at VLT finding a radial polarization across the CCD. [Paper](https://ui.adsabs.harvard.edu/abs/2020A%26A...634A..70G/abstract) published. 

![Image](instpol.jpg)

- **Moon polarization patterns in the Sky (PI: B. Pereira)**:<br/>
The scattering from the Moon in the sky produces a polarization pattern that needs to be corrected for when performing polarimetric observations in the night. We are investigating the observed pattern taken with FORS2-VLT data compared with single scattering and multiple scattering models.

<p align="center">
<img src="moonpol.jpg" alt="alt text" width=400 height=300>
</p>

- **Supernova polarization evolution (PI: A. Morales-Garoffolo)**:<br/>
We are studying the evolution of the polarization of nearby SNe with linear imaging polarimetry with CAFOS-CAHA. Polarimetric studies reveal the asymmetries of SN explosions and provide a unique view of the interstellar and circumstellar material around them.

- **Narrow absorption lines in supernovae (PI: C. Gutiérrez, S. González-Gaitán)**:<br/>
The narrow absortpion lines found in SN spectra of all types reveal the slow moving material in the line of sight towards SNe. We are investigating the frequency, strength, evolution and velocity of several species like Na I D, Ca II H & K, K I and diffuse interstellar bands for an unprecedented large sample of supernova spectra. 

- **Evolution of dust reddening law towards SNe Ia**:<br/>
We investigate if the dust reddening law, Rv, changes with phase of the evolution of type Ia supernovae. We use optical and near-infrared light-curves fitted with [SNpy](https://csp.obs.carnegiescience.edu/data/snpy) to constrain reddening laws across time. This will shed light on progenitors by constraining possible circumstellar material and dust properties towards SNe Ia.

<p align="center">
<img src="SNextinction.jpg" alt="alt text" width=600 height=400>
</p>


## Meetings
Some previous meetings:
- [CRISPinho 2020](https://amusing-muse.github.io/crispinho2020/)
- [CRISP 2020](https://amusing-muse.github.io/crisp2020/)
- [CRISP 2021](https://sn-crisp.github.io/CRISP2021/)

## Acknowledgement
CRISP is funded by FCT (PTDC/FIS-AST-31546/2017).
