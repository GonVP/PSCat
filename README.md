## Description
This repository is currently under active development as part of an ongoing PhD research about dust particles in protoplanetary disks.
Content, scripts, and documentation are being progressively updated and refined.

The 'data' directory contains the catalog of simulation models described in Vargas et al. (2025) manuscript. It includes angle-resolved scattering matrices, absorption, scattering and extinction cross-sections, and single-scattering albedo for two particle families: consolidated porous particles modeled with ADDA (Yurkin & Hoekstra, 2011) and highly porous fractal aggregates modeled with MSTM (Mackowski & Mishchenko 2011). The catalog covers the most relevant (sub)-millimeter wavelengths for the analysis of protoplanetary disk observations from the Atacama Large Millimeter/sub-millimeter Array (ALMA) and NSF's Karl G. Jansky Very Large Array (VLA): 0.87, 1.0, 3.0 and 7.0 mm. The models adopt the DSHARP dust composition (Birnstiel et al. 2018)—a mixture of astronomical silicates, carbonaceous material, and water ice—considering both cases with and without the water-ice component.

The 'models' directory contains the input models used for the MSTM and ADDA simulations. For ADDA, the input models correspond to consolidated porous particles with porosities of 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, and 0.9. For MSTM, the input models correspond to highly porous fractal aggregates with porosities of 0.94, 0.98, and 0.99.

The 'data_analysis.ipynb' notebook contains the Python script for loading, processing, and visualizing the data catalog, including both MSTM and ADDA particle models and the MIE compact spheres for reference. To execute the notebook, download the 'data' directory and place 'data_analysis.ipynb' inside it.

## Data Release
Version 1.0 (November 14, 2025): 
  Wavelength coverage: 0.87, 1.0, 3.0, and 7.0 mm. 
  Particle size range: 0.01 µm to 1 mm.

## License

This catalog is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).  

Please cite the following paper if you use this catalog:
Vargas et al. (2025): Modeling (Sub)-Millimeter Scattering Properties of Fractal and Consolidated Porous Particles: Applications to Protoplanetary Disks.

Submitted manuscript currently under peer review.

## Contact
gvargas@iaa.es

Gonzalo Vargas

Predoctoral Researcher at Instituto de Astrofísica de Andalucía (IAA-CSIC), Granada-Spain.

