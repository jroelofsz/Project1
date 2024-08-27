# Chicago Public Health Analysis

This investigation aims to identify correlations between various public health indicators across Chicago's community areas. By highlighting areas lacking essential resources, the analysis can pinpoint regions where public policy or legislative action may be necessary. The goal is to uncover communities disproportionately affected by these health indicators, guiding targeted improvements and better al

## Why is this important?

This issue warrants investigation because it enables us to identify correlations between various public health indicators across Chicago's community areas (see reference below). By pinpointing specific community areas that lack essential amenities or resources needed to address these health markers, our analysis could highlight areas where public policy interventions or legislative action are necessary. This approach may also shed light on communities that are disproportionately impacted by these public health indicators, providing valuable insights for targeted improvements. The goal is to find which region(s) have higher vulnerability and may be in need of more focus from local municipalities as well as providing better targeting for funds allocation.


## Questions Asked
    - Which community areas have high teen birth rates, does it have any relation with poverty level ? Is there a correlation between elevated rates of teen births and a lack of a high school diploma?
    - Does a higher rate of crowded housing result in a higher rate of Tuberculosis?
    - Do certain socioeconomic brackets have a higher risk of certain health markers?
    - Which community areas have a high IMR? Does IMR correlate with  early prenatal care? Is early prenatal care available in Chicago proving effective from the perspective of IMR? Does early prenatal care correlate with Low Birth Weight (LBW) , and Preterm Births (PTB). Will a higher level of prenatal care result in fewer incidences of LBW and PTB?  Are there any OTHER significant drivers of these values?

## Instructions
Final analyses and graphs are all location on the main.ipynb file in this repository. If you wish to view work done by a specific collaborator, please reference the files in the `/Code Resources` folder. This has specific notebooks that each collobartor worked on for their specific portions of this project.

All photos of graphs/charts created are located in the `Out` folder. They are labeled according to which question they were created for.

Some users may find issues with dependencies with the hvplot geoviews library, adding `!pip install hvplot geoviews` to your project should satisfy this dependency.


## Authors

- [Jacob Roelofsz](https://github.com/jroelofsz)
- [Sarika Sharma](https://github.com/SShar-del)
- [Didem Blum](https://github.com/DidemBl)


## Environment Variables

To run this project, you will need to create a file called api_keys.py in your environment. You will then need to add a 

`geoapify_key`

variable to this file. This will allow you to run the geoapify API to view the data on a map.


## Optimizations

- Added Column to identify 'Region' name. this is the caloquial name identifying groups of community areas.
- Created linear regression function to speed up EDA and easily grab pertinent statistical values related to the analysis.

