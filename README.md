# Introduction

This script was made to make the calculation of the optical bang gap (Eg) a bit more streamlined and to make the visualizations uniform.

Simply put, the Eg is the energy difference between the valence band and conduction band of a material. In other words the Eg equates to the minimum amount of energy required for an electron to break free from its bound state.
Knowing the value of Eg gives important insight into a materials properties. Depending on the size of the Eg we differentiate materials as conductors, semiconductors and insulators.

There are different approaches for calculating the Eg. In this project I chose the [Tauc](https://en.wikipedia.org/wiki/Tauc_plot) plot method using calculations for allowed transitions in direct and indirect types of Eg.

# Data
For the example data I chose my own experimental data obtained by UV-VIS spectroscopy of transparent titanium dioxide thin films. In this measurements ultra-violet and visible light passes through the sample or is reflected off the surface of the sample. We then track track, using special sensors, how that light changes in intensity in respect to its wavelength. 
These measurements showed how much of the light dependent on its wavelength was absorbed (Absorbance), reflected (Reflectance) or passed through (Transmittance) the material. From these simple observations and the measure thickness of the films we can calculate the optical Eg using the Tauc method.

# Tools
__Python__  
Linear regression  
Tauc plots  
UV-Vis spectroscopy - optical properties of the thin film  
Profilometry - thickness of the thin films  
