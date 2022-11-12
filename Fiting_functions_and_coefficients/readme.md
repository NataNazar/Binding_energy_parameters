# Fitting formulas, coefficients, and mean squared errors

 We want to provide the opportunity to use our results to researchers who use the polynomial fitting formula approach.


## For hydrogen stars

The fitting formula for a single hydrogen star with an any initial mass $M_{\text{ZAMS}}$ and any  metallicity value  $Z$  for the evolutionary period from the beginning of hydrogen    shell burning till the drop of the luminosity at the beginning or the moment of helium   shell 
burning:

$$ \log_{10} \lambda_{\text{b}} = 
b_1 \ \log_{10} \left( \dfrac{R}{R_{\odot}}\right) + 
b_2 \ \log_{10} \left( \dfrac{R}{R_{\odot}}\right)^2 +
b_3 $$

and from the beginning of luminosity's drop till the beginning of  carbon burning or till the moment when the star will become Wolf-Rayet star.
When the total amount of hydrogen in a star falls below 3\%, we refer to it as a Wolf-Rayet star:

$$ \log_{10}\left(\dfrac{1}{\lambda_{\text{b}}}\right) = b_4 \  \log_{10} \dfrac{L_{\text{eff}}}{L_{\text{eff},0}} + b_5 
$$ 

We have obtained  $b_1$, $b_2$, $b_3$, $b_4$ and $b_5$ coefficients for a wide range of initial masses $M_{\text{ZAMS}}$ of hydrogen  stars (from 2.0 $M_{\odot}$ till 600 $M_{\odot}$)  
and presented them in tables for all considered values of metallicities. 
Also, the tables contain mean squared error (MSE) for results each obtained fitting formula.  
During the fitting procedure, we excluded the values of the binding energy parameters when the star became a Wolf-Rayet star.
 
Since the resulting formulas require using a separate set of coefficients for each star, this may need to be more user-friendly.
We have decided to provide an even more general fitting formula for easier results usage. This formula should provide a compact set of coefficients for the range of initial stellar masses.
In order to do so,  we applied the fitting formula for the coefficients $b_1$, $b_2$, $b_3$, $b_4$ and $b_5$ for the stars of the different initial mass ranges 
and one selected metallicity value $Z$:

$$ b_{1}=a_{1} \log_{10} M_{\text{ZAMS}} + a_{2} $$

$$ b_{2}=a_{3} \log_{10} M_{\text{ZAMS}} + a_{4} $$

$$ b_{3}=a_{5} \log_{10} M_{\text{ZAMS}} + a_{6}  $$

$$ b_{4}=a_{7} \log_{10} M_{\text{ZAMS}} + a_{8} \left( \log_{10} M_{\text{ZAMS}} \right)^2 +a_9 $$ 

$$ b_{5}=a_{10} \log_{10} M_{\text{ZAMS}} + a_{11} \left( \log_{10} M_{\text{ZAMS}} \right)^2 +a_{12} $$

We have obtained  $a_1$, $a_2$, $a_3$, $a_4$, $a_5$, $a_6$, $a_7$, $a_8$, $a_9$, $a_{10}$, $a_{10}$ and $a_{12}$ 
coefficients and MSE for the following initial mass ranges  $M_{\text{ZAMS}}$ of  hydrogen stars:
- $2.0-7.5 \ M_{\odot}$  
- $8.0-20.0 \ M_{\odot}$ 
- $25.0-50.0 \ M_{\odot}$  
- $60.0-90.0 \ M_{\odot}$ 
- $100-600 \ M_{\odot}$  
and  printed them  in tables. These mass ranges were chosen to obtain the lowest possible median value of mean squared error (MSE).

 
## For helium stars

Also, we obtained the fitting formulas for binding energy parameters of naked helium stars. 
The selection of fitting functions for the binding energy parameters for helium stars was much simpler due to the smooth dependence of the parameter on the stellar radius.
We produced the fitting formula for a single helium star with an initial mass $M_{\text{ZAMS}}$ and metallicity $Z$ 
from the beginning of carbon-oxygen core production till the end of PARSEC tracks:

$$ \log_{10} \lambda_{\text{b}} = b_1 \ \log_{10} \left( \dfrac{R}{R_{\odot}}\right) + b_2  $$

We obtained $b_1$ and $b_2$ coefficients and MSE for helium stars with every considered value of  initial mass (from 2.0 $M_{\odot}$ till 350 $M_{\odot}$) and metallicity  and presented them in tables.
Also, we have chosen more general fitting formulas with a compact set of coefficients for helium stars.
We produced the fitting formula for the coefficients $b_1$ and $b_2$ for the helium stars of the different initial mass ranges   and  selected metallicity value:

$$ b_{1}=a_{1} \log_{10} M_{\text{ZAMS}} + a_{2} \left( \log_{10} M_{\text{ZAMS}} \right)^2 +a_3 $$

$$ b_{2}=a_{4} \log_{10} M_{\text{ZAMS}} + a_{5} \left( \log_{10} M_{\text{ZAMS}} \right)^2 +a_6 $$

We obtained $a_1$, $a_2$, $a_3$, $a_4$, $a_5$ and $a_6$ coefficients and MSE  for the following initial mass   ranges   of helium stars:
- $2.0-7.0\,\, M_{\odot}$  
- $7.2-22.0\,\, M_{\odot}$  
- $24.0-70.0\,\, M_{\odot}$ 
- $75.0-350.0\,\, M_{\odot}$ 
and presented in the tables. These mass ranges were chosen to obtain the lowest possible median value of mean squared error (MSE).


## Comparison of fitted value and precise value of $\lambda_{\text{b}}$-parameters for hydrogen and helium stars

PLOTS



 
