# ISBA-A-gs Land Surface Model Simulations: GPP, ET, and WUE

## Overview

This repository provides the input datasets, vegetation characteristics, meteorological forcing data, and simulation outputs used to perform land surface modelling with the **ISBA-A-gs (Interactions between Soil, Biosphere, and Atmosphere – Generic) model**.

The repository is associated with the research study investigating the dynamics of Gross Primary Productivity (GPP), Evapotranspiration (ET), and Water Use Efficiency (WUE) across two contrasting agricultural sites located in France and India.

The simulations were conducted at the following two study sites:

- **FR-Lam:** Lamasquère, France.
- **Ind-IITH:** Indian Institute of Technology Hyderabad (IITH), Telangana, India.

The repository aims to provide transparent access to the datasets and model simulation outputs used in this study, supporting research reproducibility, data interpretation, and further applications of the ISBA-A-gs model in agricultural ecosystems.

## Repository Structure

The repository is organized into two main folders, corresponding to the two study sites.

*Note: The subfolder names above illustrate the recommended organization. Adapt them to match the actual uploaded files.*

## Study Sites

### 1. FR-Lam – Lamasquère, France

This site represents an agricultural ecosystem located in southwestern France. The meteorological forcing datasets and vegetation characteristics were used to configure and drive the ISBA-A-gs model simulations.

The corresponding input datasets and model outputs are provided in the `FR-Lam` directory.

### 2. Ind-IITH – Indian Institute of Technology Hyderabad, India

This site is located at the Indian Institute of Technology Hyderabad, Telangana, India, and represents an agricultural ecosystem under semi-arid climatic conditions.

The meteorological forcing data and vegetation characteristics were used to parameterize and drive the ISBA-A-gs model for simulating ecosystem carbon and water fluxes.

The corresponding input datasets and model outputs are provided in the `Ind-IITH` directory.

## Input Datasets

The input datasets provided for both study sites consist of two major categories:

### 1. Meteorological Forcing Data

Meteorological variables required to drive the ISBA-A-gs model, including the relevant atmospheric and surface forcing variables, are provided for each study site.

These datasets include the meteorological parameters required for simulating land–atmosphere exchanges and ecosystem carbon and water fluxes.

### 2. Vegetation Characteristics

Vegetation-related parameters required for configuring the ISBA-A-gs model are provided separately for both sites.

These datasets describe the vegetation properties and characteristics required for representing crop development, canopy functioning, and associated physiological processes within the model.

## Model Simulation Outputs

The repository contains ISBA-A-gs simulation outputs for the following ecosystem variables:

- Gross Primary Productivity (GPP): Simulated ecosystem carbon uptake.
- Evapotranspiration (ET): Simulated ecosystem water vapour flux.
- Water Use Efficiency (WUE): Ecosystem carbon gain relative to water loss, evaluated using the corresponding GPP and ET simulations.

The simulation outputs are organized according to the respective study sites, allowing independent examination and comparison of modelled carbon and water fluxes between France and India.

## Model Description

ISBA-A-gs is a land surface modelling framework that represents exchanges of energy, water, and carbon between the land surface, vegetation, and atmosphere. The model incorporates vegetation physiological processes, including photosynthesis and stomatal regulation, to simulate ecosystem carbon and water fluxes.

In this study, ISBA-A-gs was used to investigate GPP, ET, and WUE dynamics across two contrasting agricultural environments. Please read the full manual of ISBA-A-gs before working and you access manual here: https://www.umr-cnrm.fr/surfex/spip.php?article187


## Data Availability and Reproducibility

All input datasets and corresponding ISBA-A-gs simulation outputs associated with the study are made available in this repository to facilitate transparency and reproducibility of the research.

The repository is intended to support researchers interested in:

- Land surface modelling and ecosystem process simulations.
- Agricultural carbon and water fluxes.
- Gross primary productivity and evapotranspiration modelling.
- Ecosystem and crop water use efficiency.
- Comparative analysis of agricultural ecosystems across different climatic conditions.

## Acknowledgements

The authors acknowledge the institutions, research teams, and data providers associated with the FR-Lam and Ind-IITH study sites for providing the datasets and scientific support required for this research.


Citation: Chintala, S., Jarlan, L., Rivalland, V., Boone, A., Dare-Idowu, O., Le Dantec, V., Boulet, G., Kambhammettu, B.P.,
Brut, A., 2026. Understanding ecosystem gross primary productivity, evapotranspiration, and water use
efficiency of maize using ISBA-A-gs land surface model over temperate and tropical semi-arid climates.
EGUsphere, preprint en discussion pour Biogeosciences. doi:10.5194/egusphere-2026-3119


## Contact

For questions regarding the datasets, model simulations, or repository contents, please contact:

Syam Chintala 
Department of Civil Engineering  
Indian Institute of Technology Hyderabad (IITH), India.
