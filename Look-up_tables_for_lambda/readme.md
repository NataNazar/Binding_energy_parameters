# Look-up tables for all obtained binding energy parameters 

## Core-envelope boundary criteria

In our work, we considered the core as a hydrogen-exhausted region in the star's center.
To determine the boundary between the helium and carbon cores, we need to know the distribution of the hydrogen and helium fractions inside the star.
We get these physical parameters from PARSEC simulation results.
We found the mass and radius of a stellar core using information about the star's chemical composition. 

We tried different threshold values of hydrogen fraction and investigated how they affect the CEE with respect to adopting different criteria for defining the core-envelope boundary.
We used following  criteria  $X_{\text{H}}=0.2, \ 10^{-2}, \ 10^{-3}, \  10^{-5}, \ 10^{-7}, \ 10^{-9}$ 
of   hydrogen fraction  for  helium core and $X_{\text{He}}=0.2, \ 10^{-2}, \ 10^{-3}, \ 10^{-5}, \ 10^{-7}, \ 10^{-9}$ 
of helium fraction $X_{\text{He}}$ for  developed carbon-oxygen core.


# Example of look-up table



|  t/Myrs  | M/$M_{\odot}$  |  R/cm  |     L/L⊙   |    lam_g1  |   lam_b1  |   lam_h1   |  lam_g2  |   lam_b2   |  lam_h2   |
| ------------------|:-------------:| ----:|----:|------:|------:|-------:|-------:|-------:|-------:|
| 2.501e-01 |  1.990e+00  | 2.477e+10 |  2.307e+03 | 1.312e-01 | 1.894e-01 | 2.647e-01 | 1.312e-01 | 1.894e-01  | 2.647e-01 |
| 3.820e-01 | 1.985e+00 | 2.487e+10 | 2.337e+03 | 1.187e-01 | 1.697e-01 | 2.342e-01 | 1.187e-01  | 1.697e-01 | 2.342e-01 |
| 4.582e-01 | 1.982e+00 | 2.494e+10 | 2.356e+03 | 1.176e-01 | 1.682e-01 | 2.323e-01 | 1.176e-01 | 1.682e-01 | 2.323e-01 |


where lam_g1,   lam_b1,   lam_h1  are binding energy parameters with $X_{\text{H}}=0.2$ core criteria
and lam_g2,   lam_b2,   lam_h2 are binding energy parameters with $X_{\text{H}}=  10^{-9} $ core criteria.


 
