# tRIBS 2023
tRIBS source files for development 

This verison of tRIBS incorporates significant developement, with the latest modifications made by Josh Cederstrom over the course of his degree. This version also includes fixes from Ara Ko, Carlos Lizarraga, and Xiaoyang. It does not include updates to make files, as a current goal is to bypass this step by using CMake.

Fixes includes:
- various bug fixes that may or may have not been incorporated into the main code vesrion
- additons to model outputs to meet the needs of my project e.g. adding snowpack sublimation and evaporation to the outputs
- changes in variable outputs for certain files e.g. replacing certain variables in dynamic file with the cumulative values
- additons to snow model like windspeed reduction below the canopy and ability to specify snow liquid water holding capcity in the input file.

To find these changes search for "CJC", "CJC2019", "CJC2020", and "CJC2021"

This version does incorporate the ability to load soil parameters in the form of grids.
