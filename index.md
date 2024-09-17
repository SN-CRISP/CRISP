## Welcome to CRISP

CRISP is a multi-faceted project to study extinction towards supernovae (SNe) and their environments through a variety of observational techniques including photometry, integral field spectroscopy and polarimetry of both SNe and their hosts, as well as machine learning tools and radiative transfer modeling.

<p align="center">
<img src="crisp_logo_cut.jpg" alt="alt text" width=300 height=200>
</p>

[Team and collaborators](#team-and-collaborators) &ensp; [Papers](#principal-papers) &ensp; [Projects](#projects)


## Team and collaborators

Alejandro Yepes <br/>
Alessandro Razza <br/>
Ana Mourão (CENTRA-IST)<br/>
Ana Paulina-Afonso (IA-Porto)<br/>
Antonia Morales-Garaffolo (U.Cádiz)<br/>
Alberto Krone-Martins (U.Cal-Irvine)<br/>
Beatriz Pereira (CENTRA-IST)<br/>
Caterina Corte-Real (CENTRA-IST)<br/>
Claudia Gutiérrez (ICE-CSIC, Barcelona)<br/>
[Francisco Förster](https://fforster.github.io/) (U.Chile)<br/>
Gonçalo Martins (CENTRA-IST)<br/>
João Duarte (CENTRA-IST)<br/>
João Silvestre (CENTRA-IST)<br/>
João Gonçalves (CENTRA-IST)<br/>
Joe Anderson (ESO)<br/>
[Lluis Galbany](https://lgalbany.github.io/) (ICE-CSIC)<br/>
Marko Stalevski (O.Belgrade)<br/>
Majda Smole (O.Belgrade)<br/>
Pedro Garcia <br/>
[Saby Goswami](https://sabygoswami.github.io/) (IAA-CSIC, Granada)<br/>
Santiago González-Gaitán (CENTRA-IST)<br/>
Thomas de Jaeger (CNRS/LPNHE/Sorbonne)<br/>

## Principal papers
- [A sample of dust attenuation laws for Dark Energy Survey supernova host galaxies](https://ui.adsabs.harvard.edu/abs/2023A%26A...680A..56D/abstract) - J. Duarte et al.
- [Dissecting the active galactic nucleus in Circinus - III. VLT/FORS2 polarimetry confirms dusty cone illuminated by a tilted accretion disc](https://ui.adsabs.harvard.edu/abs/2023MNRAS.519.3237S/abstract) - M. Stalevski, S. González-Gaitán et al.
- [Narrow absorption lines from intervening material in supernovae. I. Measurements and temporal evolution](https://ui.adsabs.harvard.edu/abs/2024A%26A...687A.108G/abstract) - S. González-Gaitán,C. Gutiérrez et al.
- [Systematic errors on optical-SED stellar-mass estimates for galaxies across cosmic time and their impact on cosmology](https://ui.adsabs.harvard.edu/abs/2022A%26A...662A..86P/abstract) - A. Paulino-Afonso et al.
- [The effects of varying colour-luminosity relations on Type Ia supernova science](https://ui.adsabs.harvard.edu/abs/2021MNRAS.508.4656G/abstract) - S. González-Gaitán, T. de Jaeger et al.
- [Spatial field reconstruction with INLA: application to IFU galaxy data](https://ui.adsabs.harvard.edu/abs/2019MNRAS.482.3880G/abstract) - S. González-Gaitán and COIN.
- [Spatial field reconstruction with INLA. Application to simulated galaxies](https://ui.adsabs.harvard.edu/abs/2023A%26A...669A.152S/abstract) - M. Smole et al.
- [EmulART: Emulating Radiative Transfer -- A pilot study on autoencoder based dimensionality reduction for radiative transfer models](https://ui.adsabs.harvard.edu/abs/2022arXiv221015400R/abstract) - J. Rino-Silvestre et al.



## Projects

### Dust from supernova environments

- **Dust attenuation slopes of high-z galaxies (PI: J. Duarte)**:<br/>
We obtain a set of dust attenuation slopes for a cosmological sample of SNe Ia from their host galaxies with broad-band photometry from the Dark Energy Survey ([DES](https://www.darkenergysurvey.org/)) complemented with available GALEX UV photometry and 2MASS NIR when available. We use the SED fitter [prospector](https://prospect.readthedocs.io/en/latest/) and [FSPS](https://dfm.io/python-fsps/current/) population synthesis code. The method is tested with simulations. We find a two-dimensional dust step that is similar in magnitude and significance to the mass-step but not equal. [Paper](https://ui.adsabs.harvard.edu/abs/2023A%26A...680A..56D/abstract) published.
<p align="center">
<img src="tau-n.jpg" alt="alt text" width=550 height=250>
</p>

- **Dust biases in galaxy environments (PI: J. Duarte)**:<br/>
Complex star-dust geometries and orientations have a significant effect on the obtention of attenuation optical depth and attenuation curves. By simulating dusty galaxies at different orientations with Monte Carlo radiative transfer modeling with [SKIRT](https://skirt.ugent.be/root/_landing.html), we examine the effect on the fitted dust parameters. 

- **Dust attenuation slope maps of AMUSING galaxies**:<br/>
We will obtain maps of dust attenuation slopes across nearby galaxies observed with Integral Fiel Spectroscopy (IFS) from the [AMUSING](https://amusing-muse.github.io/) survey. Spectra are complemented with optical, UV and NIR broad-band photometry. The method uses the SED fitter [prospector](https://prospect.readthedocs.io/en/latest/) and [FSPS](https://dfm.io/python-fsps/current/) population synthesis and is being tested with large simulations.

- **Pilot project of polarimetric studies towards galaxies: the case of Circinus (PI: M. Stalevski, S. González-Gaitán)**:<br/>
Imaging polarimetry of the nearby Circinus galaxy, host of an Active Galactic Nucleus (AGN), taken with FORS2-VLT in multiple optical bands allows the study of the geometry and dust characteristics of the central object ([Paper I](https://ui.adsabs.harvard.edu/abs/2023MNRAS.519.3237S/abstract)) and its galaxy. 

<p align="center">
<img src="Circinus.jpg" alt="alt text" width=300 height=250>
</p>

- **Polarimetric studies towards galaxies (PI: J. Silvestre)**:<br/>
The first statistical study of multi-band imaging polarimetry with optical data from FORS2-VLT and CAFOS-CAHA will deliver nearby galaxy maps of various physical characteristics like dust and magnetic field alignment. The data will be compared with Monte Carlo radiative transfer simulations with the code [SKIRT](https://skirt.ugent.be/root/_landing.html).

<p align="center">
<img src="galpol.jpg" alt="alt text" width=500 height=230>
</p>

- **Interstellar lines in IFU spectra (PI: S. Goswami)**:<br/>
We are obtaining the strength and velocity of interstellar lines like Na I D in Integral Fiel Spectroscopy (IFS) of SN host galaxies from the [AMUSING](https://amusing-muse.github.io/) survey. By fitting stellar population synthesis we subtract the stellar component and investigate the interstellar medium (ISM) tracers in the light of supernovae measurement.  


### Dust from supernovae

- **Narrow absorption lines in supernovae (PI: C. Gutiérrez, S. González-Gaitán)**:<br/>
The narrow absorption lines found in SN spectra of all types reveal the slow moving material in the line of sight towards SNe. We are investigating the frequency, strength, evolution and velocity of several species like Na I D, Ca II H & K, K I and diffuse interstellar bands for an unprecedented large sample of supernova spectra. In ([Paper I](https://ui.adsabs.harvard.edu/abs/2024A%26A...687A.108G/abstract)) we develop a new robust methodology to measure narrow lines which demonstrates that there is a substantial bias from the P-Cygni profile of the supernova in low-resolution spectra. We show that statistically there is little evolution in the strength of the sodium lines for various supernova types.  

<p align="center">
<img src="EWevol.jpg" alt="alt text" width=500 height=350>
</p>

- **Intrinsic colors of type Ia supernovae (PI: C. Corte-Real)**:<br/>
In order to properly correct for dust reddening in the line of sight of supernvoae, we need to know their intrinsic colors. These might change with intrinsic properties like lightcurve width or ejecta velocity. In this study we use several machine learning tools to look for different populations of type Ia supernovae according to color evolution and infer their intrinsic colors. 

<p align="center">
<img src="pc1.png" alt="alt text" width=500 height=300>
</p>

- **Dust extinction laws of DES supernovae (PI: J. Gonçalves)**:<br/>
We are obtaining a set of dust extinction laws for a cosmological sample of SNe Ia light-curves from the Dark Energy Survey ([DES](https://www.darkenergysurvey.org/)). We use [SNpy](https://csp.obs.carnegiescience.edu/data/snpy) to constrain reddening laws. The method is tested with simulations.

- **Supernova polarization evolution (PI: A. Morales-Garoffolo)**:<br/>
We are studying the evolution of the polarization of nearby SNe with linear imaging polarimetry with CAFOS-CAHA. Polarimetric studies reveal the asymmetries of SN explosions and provide a unique view of the interstellar and circumstellar material around them.

- **Evolution of dust reddening law towards SNe Ia (PI: A. Yepes)**:<br/>
We investigate if the dust reddening law, Rv, changes with phase of the evolution of type Ia supernovae. We use optical and near-infrared light-curves fitted with [SNpy](https://csp.obs.carnegiescience.edu/data/snpy) to constrain reddening laws across time. This will shed light on progenitors by constraining possible circumstellar material and dust properties towards SNe Ia.

<p align="center">
<img src="EBVRVST.jpg" alt="alt text" width=600 height=400>
</p>

### Impact of dust on cosmology

- **ARGAS: Artifically Redshifting of Galaxies (PI: A. Paulina-Afonso)**: <br/>
Studies have shown that type Ia supernova distance estimation improves when using an additional term related to the host galaxy mass. However, the bias and systematics of using a limited set of broad-band filters across a large redhift range has never been evaluated. With extensive simulations of nearby integral field spectroscopy (IFS) galaxies set at high redshifts, we study here the impact of effects like dimming, scaling and SED fitting in the mass-step used in cosmology for current and future SN surveys. [Paper](https://ui.adsabs.harvard.edu/abs/2022A%26A...662A..86P/abstract) published.
![Image](ARGAS.jpg)

- **Impact of varying colour-luminosity relation in type Ia supernova cosmology (PI: T. de Jaeger, S. González-Gaitán)**:<br/>
Type Ia SN cosmology has been essential in determining the accelerated expansion of the universe. However, the standardization of their luminosity to measure distances relies on a color-luminosity calibration that generally assumes a constant factor throughout the SN Ia population. We investigate in this project the effect of letting this parameter vary. [Paper](https://ui.adsabs.harvard.edu/abs/2020arXiv200913230G/abstract) published.
<p align="center">
<img src="beta_color_value.jpg" alt="alt text" width=300 height=300>
</p>


### Methods

- **Galaxy spatial field reconstruction with INLA (PI: S. González-Gaitán)**::<br/>
The spatial correlations of astrophysical quantities are normally poorly taken into account. As part of the [COIN](https://cosmostatistics-initiative.org/) collaboration, we use here the Integrated Nested Laplace Approximation ([INLA](https://www.r-inla.org/)) machinery to obtain meaningful spatial reconstructions of IFS galaxy properties. The algorithm is very powerful when there is sparsity of data. [Paper](https://ui.adsabs.harvard.edu/abs/2019MNRAS.482.3880G/abstract) published and [implementation](https://github.com/COINtoolbox/Galaxies_INLA).   

![Image](INLA.jpg)

- **1.5D SED spatial fitting (PI: P. Garcia)**:
The next step of the INLA spatial fitting applied to galaxy IFS is to simulatenously fit the wavelength and the spatial dimension. In a first 1.5D approach, we iteratively fit the SED at each spaxel with [prospector](https://prospect.readthedocs.io/en/latest/) while the spatial part is done with [INLA](https://www.r-inla.org/). 

- **Optimization of radiative transfer codes (PI: M. Smole, J. Silvestre)**:
Monte Carlo radiative transfer (MCRT) codes like [SKIRT](https://skirt.ugent.be/root/_landing.html) simulate the observed distribution of light as a function of wavelength given an initial geometry and dust composition; but this is computationally expensive. We are using the [INLA](https://www.r-inla.org/) methodology and dimensionality reduction (PCA, NMF, autoencoders) to boost MCRT modeling of Active Galactic Nuclei (AGN) and AURIGA galaxies requiring less initial photons and less compuational time. [Paper I](https://ui.adsabs.harvard.edu/abs/2022arXiv221102602S/abstract) focuses on galaxies with PCA/NMF and INLA, [Paper II](https://ui.adsabs.harvard.edu/abs/2022arXiv221015400R/abstract) on spherical geometries with variatonal autoencoders (see also: [EmulART](https://github.com/SN-CRISP/EmulART)). 

- **Instrumental field polarization of FORS2-VLT (PI: S. González-Gaitán, A Mourão)**:<br/>
Extended imaging polarization studies requires a full characterization of the instrument which is known to produce spurious polarization patterns. We study the instrumental field polarization of the FORS2 instrument at VLT finding a radial polarization across the CCD. [Paper](https://ui.adsabs.harvard.edu/abs/2020A%26A...634A..70G/abstract) published and [implementation](https://github.com/gongsale/FORS2-INSTPOL). 

![Image](instpol.jpg)

- **Moon polarization patterns in the Sky (PI: B. Pereira)**:<br/>
The scattering from the Moon in the sky produces a polarization pattern that needs to be corrected for when performing polarimetric observations in the night. We are investigating the observed pattern taken with FORS2-VLT data compared with single scattering and multiple scattering models.

<p align="center">
<img src="moonpol.jpg" alt="alt text" width=450 height=300>
</p>



## Meetings
Some previous meetings:
- [CRISPinho 2020](https://amusing-muse.github.io/crispinho2020/)
- [CRISP 2020](https://amusing-muse.github.io/crisp2020/)
- [CRISP 2021](https://sn-crisp.github.io/CRISP2021/)

## Acknowledgement
CRISP is funded by FCT (PTDC/FIS-AST-31546/2017).
