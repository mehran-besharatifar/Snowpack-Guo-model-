# Snowpack-Guo-model-
This code is simply calibrated for the Snow Water Equivalent (SWE) product.

⏳ This is just a sample: The process takes approximately 1000 seconds with 5 iterations. If more iterations are needed, it is recommended to use the Faculty's computing systems.

📊 The required data includes temperature, precipitation, and snow product rasters at a 0.01-degree resolution, as our goal is pixel-level accuracy. However, due to the large volume of these data, it is suggested that a larger resolution (e.g., 0.1-degree) be used if snow maps are not needed to reduce modeling time.

🌡️ The temperature and precipitation rasters have been produced using the PRISM model.

📑 The Excel file GUO_yearly_all_years is the output of the model.

For the Fitness Function, only Absolute Error has been used, while the original paper employed a more complex function.

⚙️ Swarm Size and other parameters must be selected by the user based on their requirements.

📍 template_tif is a raster with empty data for the basin. It can be created by reading a precipitation or temperature raster and setting its values to zero (in Python). This raster is used to store information about past time steps.

