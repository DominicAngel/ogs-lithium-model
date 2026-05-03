\# OGS Lithium Modeling Workflow



This repository contains a structured workflow for numerical modeling of geothermal systems for potential lithium extraction, using OpenGeoSys (OGS), Gmsh, and Python.



\## Project Objective



The goal of this project is to develop a reproducible and scalable modeling workflow that integrates:



\- Mesh generation (Gmsh)

\- Boundary condition definition

\- OGS project configuration

\- Numerical simulation of fluid flow



This serves as a foundation for future extensions including:

\- Reactive transport modeling (PHREEQC)

\- Sensitivity analysis and uncertainty quantification

\- Machine learning integration (surrogate models / PINNs)



\---



\## Workflow



The modeling workflow is organized into sequential steps:



1\. \*\*Mesh generation\*\*

&#x20;  - `01\_gmsh\_mesh\_generation.ipynb`

&#x20;  - Creation of structured and layered meshes with wells



2\. \*\*Boundary definition\*\*

&#x20;  - `02\_ogs\_boundary\_meshes.ipynb`

&#x20;  - Identification and extraction of boundary surfaces



3\. \*\*Project file generation\*\*

&#x20;  - `03\_ogs\_project\_file\_generation.ipynb`

&#x20;  - Construction of `.prj` files and simulation setup



4\. \*\*Simulation execution\*\*

&#x20;  - `04\_ogs\_simple\_flow\_run.ipynb`

&#x20;  - Running OGS and visualizing results



\---



\## Repository Structure



