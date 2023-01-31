<!--
  Title:  Binding energy parameters
  Description:  The page contains the binding energy parameters derived from the stellar evolution PARSEC code.
  Author: Natalia Nazarova
  -->
  <meta name='keywords' content='lambda parameters, binding energy parameters, common envelope, common envelope evolution, CE, CEE, isolated binary systems, PARSEC code, binding energy, fitting formulas, look-up tables, population-synthesis, formalism'>

  

# Binding energy parameters 
## The page contains the binding energy parameters derived from the stellar evolution PARSEC code in collaboration with Mario Spera and Alessandro Bressan.

## What is binding energy parameters?

The common envelope (CE) phase plays a crucial role in the evolution of isolated binary systems. During this phase, the drag forces between the binary system and the shared envelope shrink the orbit while the envelope expands. The amount of exchanged energy during CE evolution determines the fate of binaries and the origin of gravitational-wave sources from merging compact-object binaries.
Self-consistent hydrodynamical simulations of CE are very complex and computationally expensive. In fast population-synthesis studies, the CE phase is simulated via the ($\alpha$,$\lambda$)-formalism, where $\alpha$ parameterizes the fraction of orbital energy transferred to the envelope, and $\lambda$ is the envelope's binding-energy parameter.

## How we calculated binding energy parameters?

We calculated the binding energy parameter using different approximations. 
In the zero-level approximation, we  assume that the envelope contains only gravitational energy.
In this case, the formula for calculating the $\lambda_{\text{g}}$-parameter is: 

$$ E_{\text{bind}} =  {\displaystyle \int_{M_{\mathrm{core}}}^{M_{\text{d}}}  - G \ \frac{M(r)}{ r} \mathrm{d} m} = - G  \ \frac{M_{\text{d}} \ M_{\text{env}}}{ \lambda_{\text{g}} \ a_{\text{i}} \ r_L } $$

where $E_{\text{bind}}$ is total binding energy of the common envelope, $G$ is a gravitational constant,  
$M_{\mathrm{d}}$  is the mass of the donor star,   $M_{\mathrm{env}}$ is the mass of the stellar envelope, $a_{\text{i}} $ is the initial semi-major axis of binary system, and  $r_{\text{L}}$ is effective radius of the Roche lobe. 


A better approximation of the $\lambda$-parameter with respect to the previous one is consideration of both the gravitational and the thermodynamic energy of the envelope.
The formula for calculating the $\lambda_{\text{b}}$-parameter is:

$$ E_{\text{bind}} = {\displaystyle \int_{M_{\mathrm{core}}}^{M_{\text{d}}} \left[ - \ G \  \frac{M(r)}{ r}  + U \right] \ \mathrm{d} m } = - G \ \frac{M_{\text{d}} \ M_{\text{env}}}{ \lambda_{\text{b}} \ a_{\text{i}} \ r_L } $$

where $U$ is thermodynamic energy of the envelope.

We also considered the contribution of enthalpy to the binding energy of the envelope. While enthalpy is not a real energy source, it plays a significant role in energy redistribution and causes quasi-steady outflows from envelopes. 
The formula for the $\lambda_{\text{h}}$-parameter is:

$$ E_{\text{bind}} = {\displaystyle \int_{M_{\mathrm{core}}}^{M_{\text{d}}} \left[ - \ G \ \frac{M(r)}{ r}  + U + \frac{P}{\rho} \right] \ \mathrm{d} m} = - G \ \frac{M_{\text{d}} \ M_{\text{env}}}{ \lambda_{\text{h}} \  a_i \ r_L } $$

where $P$ is the pressure  and $\rho$  is the density of the stellar layer.

## For which stars we calculated binding energy parameters, and what we used?

PARSEC (the  **PA**dova \&  **TR**ieste **S**tellar  **E**volution **C**ode is the code to compute stellar evolutionary tracks.
Information about the **PARSEC** code and its updates can be found in the following papers:
- "PARSEC evolutionary tracks and isochrones including seismic properties"  [Montalbán, J. & Bressan, A. et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018IAUS..334..343M/abstract)
- "A New Generation of PARSEC-COLIBRI Stellar Isochrones Including the TP-AGB Phase" [Marigo, P. &  Girardi, L. et al (2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...835...77M/abstract)
- "New PARSEC database of alpha enhanced stellar evolutionary tracks and isochrones for Gaia" [Fu, X. & Bressan, A. et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016IAUFM..29B.144F/abstract)
- "New evolutionary tracks of massive stars with PARSEC" [Chen, Y. & Bressan, A. et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015IAUGA..2257534C/abstract)
- "New PARSEC evolutionary tracks of massive stars at low metallicity: testing canonical stellar evolution in nearby star-forming dwarf galaxies" [Tang, J. &  Bressan, A. et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014MNRAS.445.4287T/abstract)
- "Improving PARSEC models for very low mass stars" [Chen, Y. & Girardi, L. et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014MNRAS.444.2525C/abstract)
- "New PARSEC evolutionary tracks of massive stars at low metallicity: testing canonical stellar evolution in nearby star-forming dwarf galaxies" [Tang, J. & Bressan, A. et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014MNRAS.445.4287T/abstract)
- "PARSEC: stellar tracks and isochrones with the PAdova and TRieste Stellar Evolution Code" [Bressan, A. & Marigo, P. et al. (2012)](https://ui.adsabs.harvard.edu/abs/2012MNRAS.427..127B/abstract)

We used the **PARSEC** code to calculate binding energy parameters for non-rotating hydrogen stars with metallicities $Z$=0.0001, 0.0005, 0.001, 0.002, 0.004, 0.006, 0.008, 0.014, 0.017, 0.02 and  48 values of initial masses in a logarithmic scale in the range between 2.0 $M_{\odot}$ and 600.0 $M_{\odot}$.

We also considered the possibility that helium stars can act as a donor in the process of CEE.
Helium stars are stars that have completely lost all hydrogen  through either stellar winds or mass transfer in binaries or did not have it at the beginning of the Main Sequence. We used the **PARSEC** code to simulate the evolution of non-rotating helium stars with varying metallicities $Z$=0.0001, 0.0002, 0.0005, 0.001, 0.002, 0.004, 0.006, 0.008, 0.01, 0.02, 0.03, 0.05 and of
and  for  78 log-spaced  values of initial masses in the range between 2.0 $M_{\odot}$ and 350.0 $M_{\odot}$. 

## Which data are we providing?

We propose to use the obtained $\lambda$-parameters in the form of tables containing the following data: the mass, radius, effective temperature, and luminosity of the star during stellar evolution.

We also present the obtained fitting functions with coefficients and the mean squared errors  (MSE) for the fitted values compared to the exact ones.


