### Groundwater Level Visualization and Layer Assignment Tool for the Central Valley Basin (C2VSimFG v2.0)

This repository contains a preprocessing tool designed to enhance hydrogeologic analysis by integrating and visualizing groundwater levels, screened intervals (perforated well intervals), and confining units within the Central Valley Basin. The tool aligns these data with the modeling layers of the **C2VSimFG v2.0 Integrated Numerical Surface-Water-Groundwater Flow Model**.

#### Objectives
The primary goal is to improve understanding of hydrogeologic systems by combining:
- **Groundwater level measurements** from CASGEM website
- **Screened intervals** derived from well construction reports
- **Aquitard information** from authoritative sources, including:
  - [USGS Water Supply Paper 1999-H](https://pubs.usgs.gov/publication/wsp1999H) by M.G. Croft
  - [COGG 3D Geologic Model](https://webapps.usgs.gov/cogg/model/tularemodel.twig)

#### Features
The Python script developed in this project overlays these datasets to determine which monitoring wells correspond to specific layers in the **C2VSimFG v2.0** model. This facilitates:
- Accurate assignment of groundwater measurements to appropriate hydrogeologic units.
- Improved modeling of surface-water and groundwater interactions.

This tool is intended for researchers and practitioners working on hydrogeologic modeling in the Central Valley Basin.
