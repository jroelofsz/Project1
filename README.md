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

The final analyses and visualizations can be found in the `main.ipynb` file within this repository. If you're interested in exploring the contributions of specific collaborators, please refer to the notebooks located in the `/Code Resources` folder. Each notebook corresponds to the unique portions of the project handled by different team members.

All graphs and charts created during this project are stored in the `Out` folder. They are meticulously labeled to correspond with the specific research questions they address.

**Note:** If you encounter issues with dependencies related to the `hvplot` and `geoviews` libraries, you can resolve them by adding `!pip install hvplot geoviews` to your project environment.



## Authors

- [Jacob Roelofsz](https://github.com/jroelofsz)
- [Sarika Sharma](https://github.com/SShar-del)
- [Didem Blum](https://github.com/DidemBl)


## Environment Variables

To run this project, you will need to create a file named `api_keys.py` in your environment. Inside this file, add the following variable:

```python
geoapify_key = "your_api_key_here"
```

### How to Set Up Your Geoapify API Key

To utilize the Geoapify services in this project, follow these steps to set up your API key:

1. **Sign Up for a Geoapify Account:**
   - Visit the [Geoapify website](https://www.geoapify.com/).
   - Sign up for an account if you don’t already have one.
   - Once logged in, navigate to the API keys section of your dashboard.

2. **Generate an API Key:**
   - In the API keys section, click on the option to create a new API key.
   - Name your key and generate it. Make sure to copy the key somewhere safe.

3. **Create an `api_keys.py` File:**
   - In your project directory, create a new file named `api_keys.py`.
   - Open the file and add the following line of code, replacing `your_api_key_here` with the key you generated:




## Optimizations

- Added a column to identify the 'Region' name, representing the colloquial grouping of community areas. This was done through manual data manipulation.
- Developed a linear regression function to streamline Exploratory Data Analysis (EDA) and quickly extract pertinent statistical values relevant to the analysis.


