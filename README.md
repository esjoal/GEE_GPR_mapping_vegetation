# Mapping vegetation traits in Google Earth Engine using Gaussian process models and the Sentinel-2 top-of-atmosphere product.
## (Under construction)

Author: José Estévez  
Code: Matías Salinero-Delgado
\
\
This is a guideline of running a GPR model for mapping vegetation variables on Google Earth Engine (GEE), as proposed in Estévez et al., 2022.

* Please, **click the link** below to get access to the GEE repo (a GEE account is required):  
https://code.earthengine.google.com/?accept_repo=users/jose_estevez/S2TOA_GPR_MapVegetation  
* After **accept** to add the code in your GEE account, you should click the **refresh** button.
* Then you should be able to see the code in the **Reader** section  under the Scripts tab.

<p align="center">
  <img src="https://user-images.githubusercontent.com/99983732/159911620-0acb4639-6b5f-4abf-a764-c1feaf1caa50.png" width = '35%'>
</p>

<!-- (If you are not a GEE user and interested in the apps, please visit: Earth Engine Apps **(pending for update)**  -->

Please cite the code as: Estévez, J., Salinero-Delgado, M., Berger, K., Pipia, L., Rivera-Caicedo, J.P., Wocher, M., Reyes-Muñoz, P., Tagliabue, G., Boschetti, M., Verrelst, J., 2022. Gaussian processes retrieval of crop traits in Google Earth Engine based on Sentinel-2 top-of-atmosphere data. Remote Sens. Environ. 273, 112958. https://doi.org/10.1016/J.RSE.2022.112958.

Please email me at jose.a.estevez@uv.es for any further information.   

The GEE repository includes the codes for some mapping demos:

**1. Mapping at local scale**  
(Run the script 'localScaleGPR': In line 15 you can change to the variable you want to map)

![image](https://user-images.githubusercontent.com/99983732/155011559-29060772-a883-45fe-b296-3934fb410823.png)
 
**2. Mapping at national scale**  
(Run the script 'nationalScaleGPR': In line 3 you can change to the country you want to map)
 
![image](https://user-images.githubusercontent.com/99983732/155011342-e8c0726d-f9fd-4552-a859-a359709acffe.png)

**3. Mapping uncertainties**
