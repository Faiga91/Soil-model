# Soil-model
The files Tomelloso, Huesca and Almeria contains the weather datasets between 2010 and 2019, Tomelloso only contains 2011-2019.
color_map_xxx contains the tables that relate the irrigation delay with the stress caused to the plant.
Soil_model, easy code that simulates and plots the Volumetric water content every 5 minutes.

**Smart_model** Is the principal simulaton file, Includes the plotting functions in the last cell, they must be run before running the simulations. At the end of the first cell we can find some commented functions to carry different simulations, above we find the main method of the file and above that the selection of parameters for the simulations.

Eto package must be installed before the simulations, the instructions can be found in https://pypi.org/project/ETo/
For Conda, ETo can be installed as "conda install -c mullenkamp eto"
