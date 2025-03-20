We have modified the CWatM model in the evaporation, soil, and output modules to improve the calculation and output of crop yield.

In the evaporation and soil modules, we introduced additional conditions and variables to make crop yield calculations more accurate and better aligned with the objectives of this study. The relevant modifications are located in lines 8–176 and 180–238 of the code.

In the output module, we improved the output process by dynamically determining the dimensionality of the output variables, allowing for more flexible and precise output of the results. The corresponding modifications can be found in lines 242–265.
Evapotation Model
