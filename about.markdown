---
layout: home
title: about
permalink: /about/
---

## **<center>Research picture</center>**

![research-flow](../images/research-flow.png){:height="50%" width="100%"}

# Galaxy clusters

>## Intracluster medium  

\*** Study the bayron distribution based on simulated galaxy clusters. ***

In <a href="https://ui.adsabs.harvard.edu/abs/2020MNRAS.495.2930L/abstract" target= "_blank"><font color="#0000dd">Li et al. (2020)</font></a>, we conducted an *extensive* examination of the dispersion and self-similarity within profiles and distributions of various stellar and gas properties, including mass, metallicity, stellar age, gas temperature, and the (specific) star formation rate (SFR). Our analysis was grounded in the catalog of galaxy clusters from The Three Hundred project, which incorporates two hydrodynamical simulations and three semi-analytical models. Through comparisons with observational results (**optical** and **X-ray**), we found that the shape and the scatter of the gas density profiles match well the observed trends including the reduced scatter at large radii which is a signature of self-similarity suggested in previous studies.
<u>However, we did not find any clear radial dependence of stellar age, metallicity, and (s)SFR.</u>


As a continuation of studying ICM, we subsequently pay attention to the theoretical evolution of gas and stellar physical profiles with two hydrodynamical simulations Gizmo-SIMBA and Gadget-X through the tracking of their progenitors <a href="https://ui.adsabs.harvard.edu/abs/2023MNRAS.523.1228L/abstract" target= "_blank"><font color="#0000dd">Li et al. (2023)</font></a>. The profiles are explored beyond *r*<sub>500</sub> from *z* = 4 to *z* = 0. The agreements between the two runs and observations are mostly at outer radii *r* > 0.3*r*<sub>500</sub>, <u>in line with the self-similarity assumption</u>, while Gadget-X shows better agreements with the observed gas profiles in the central regions compared to Gizmo-SIMBA. The evolution trends are generally consistent between the two simulations with slightly better consistency at outer radii. In detail, the gas density profile shows less discrepancy than the temperature and entropy profiles at high redshift. The differences in the cluster center and gas properties imply **different behaviors of the AGN models** between Gadget-X and Gizmo-SIMBA, with the latter, maybe too strong for this cluster simulation. 

![research-flow](../images/research/ICM.png ){:height="50%" width="100%"}
*<font size=1>The evolution of gas mass density (left), temperature (middle) and entropy (right) profiles normalized by critical density of the universe from z=4 to z=0. The middle panel shows the ratio between the normalized density profiles at z &ge; 1 and that at z = 0. The bold navy blue line marks the scatter range of the density at z = 0. The bottom panel shows the ratio between the density in Gadget-X and Gizmo-SIMBA at the same redshift.</font>*



>## Galaxy Dynamics

\*** Estimate the mass of galaxy clusters in various dynamical models. ***

We carry out a comprehensive investigation on these aspects by applying a relatively new dynamical model (**oPDF**) to simulations of galaxy clusters (<a href="https://ui.adsabs.harvard.edu/abs/2021MNRAS.505.3907L/abstract" target= "_blank"><font color="#0000dd">Li et al. 2021</font></a>). We compare the systematics in cluster and galactic halos with different types of tracers including dark matter particles, intracluster stars and galaxies. We find that the dynamical state of satellite galaxies is close to that of dark matter particles, while intracluster stars are less in a steady state, resulting in a larger systematic uncertainty in mass. In addition, we introduce the effective number of phase-independent tracer particles to separate statistical and systematic errors, which is a relatively unexplored and very interesting technique. <u>More importantly, our conclusions are largely applicable to other steady-state dynamical models including the spherical Jeans equation.</u>


![research-flow](../images/research/oPDF.png ){:height="50%" width="100%"}
*<font size=1>Left: The best-fitting mass and concentration parameters of cluster and galactic haloes using dark matter particles as tracers. Only smooth halo particles (i.e., not within subhaloes) are used for the fitting. Each grey and blank point shows the best-fitting parameters for one cluster and galactic halo, respectively. Right: A comparison of the 1-sigma scatters in the best-fitting halo mass and concentration parameters, when different types of tracers are used.</font>*


>## Groups and Protoclusters

\*** Construct the groups and protocluster candidate catalogue in HSC and CLAUDS deep region. ***

In <a href="https://ui.adsabs.harvard.edu/abs/2022ApJ...933....9L/abstract" target= "_blank"><font color="#0000dd">Li et al. (2022b)</font></a>, we used the extended halo-based group/cluster finder to search groups and protocluster candidates from the joint CLAUDS and HSC-SSP deep **photometric** data, which allows us to extend a wide redshift range (0 < *z* < 6). You can find the details of this catalog in **Products**.

-------------------------------------------------------
# High-redshift Galaxy

>## JWST galaxies

The JWST/NIRCam mock images for the galaxies at the epoch of reionization have been generated from the SIMBA simulation, using the dust radiative transfer package Powderday. The example of image is shown in **Products**.   

-------------------------------------------------------
# Techniques

>## Machine Learning

### 1. Random Forest

We investigated the importance of various dynamical features in predicting the dynamical state of galaxy clusters based on the **Random Forest** machine-learning approach <a href="https://ui.adsabs.harvard.edu/abs/2022MNRAS.514.5890L/abstract" target= "_blank"><font color="#0000dd">Li et al. (2022a)</font></a>. Our input catalog includes the dynamical features constructed from hydrodynamical simulations directly and mock maps in the *optical*, *X-ray*, and *Sunyaev–Zel’dovich* channels. Among all the features studied, we find the virial ratio to be the most important single feature. The features calculated directly from the simulations and in three dimensions carry more information on the dynamical state than those constructed from the mock maps. We provide a quantitative reference for selecting the best features to discriminate the dynamical state of galaxy clusters in both simulations and observations.

![oob](../images/research/one_oob_sqrt2.png){:height="30%" width="100%"}
*<font size=1>Blue histograms show the out-of-bag scores of different features, with red errorbars showing their uncertainties. Note a negative out-of-bag score means a very low feature importance, i.e., the prediction of the target variable based on this feature is even worse than simply using the mean for the prediction. The top panel shows results for features constructed from simulations. Middle panels show results for features measured from the SZ and X-ray maps. The bottom panel is for all centroid position and position offsets related features.</font>*

### 2. Convolutional Neural Network

The architecture of CNN has been constructed already.


<video width="320" height="240" controls autoplay>
    <source src="../images/research/ELUCID_coma.mp4" type=video/mp4>
     COMA cluster in ELUCID simulation 
</video>
