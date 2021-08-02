# Stellar_masses_for_GLADE+
Codes of the stellar mass and merger rate estimation. 

## Project description

The stellar mass of galaxies means the sum of the mass of their living and remnant stars. This is a key parameter of the formation and evolution of galaxies, but it shows strong correlation with the merger rate of compact binaries. Thus stellar mass could help find the host galaxies of gravitational waves.

The most precise method of stellar mass estimation is spectral energy distribution fitting, but this requires values in numerous magnitude bands.
However, the infrared magnitudes are good tracers of stellar mass, so we can provide an estimation based on them.

We selected two methods from the literature to add this parameter to the new version of Galaxy List for Advanced Detector Era to help the identifying of host galaxies of compact binaries.


## Description of the notebooks in this repository:
- *wise_mag_err.ipynb* writes out the error of WISE w1 magnitude.
- *create_working_catalog.ipynb* prepares the data for the stellar mass estimation.
- *Stellar_mass_estimation_short_version_2105.ipynb* contains the stellar mass estimation for GLADE+ galaxies.
