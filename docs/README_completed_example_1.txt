-------------------
GENERAL INFORMATION
-------------------


1. Title of Dataset: Hyperspectral Reflectance Data for Flowers, Fruits, Bark, and Leaves of Plants on Barro Colorado Island, Panama


2. Author Information

  First Author Contact Information
        Name: Daria Lipsky
           Institution: Smithsonian Tropical Research Institute
        

  Corresponding Author Contact Information
        Name: Helene C. Muller-Landau
           Institution: Smithsonian Tropical Research Institute
           Email:mullerh@si.edu


  Author Contact Information (if applicable)
           Name: Lily Pitcher
           Institution: Smithsonian Tropical Research Institute


  Author Contact Information (if applicable)
           Name: Juan Camilo Osorio-Ospina
           Institution: Smithsonian Tropical Research Institute

3. Abstract 
  
This dataset contains hyperspectral reflectance measured on flowers, fruits, bark, and leaves of plants collected on Barro Colorado Island (BCI), Panama. Samples were collected mostly from fallen material on the forest floor or from understory plants. Samples were placed in individual zipper storage bags in a cooler with ice for transport back to the lab, where hyperspectral reflectance was measured using an ASD FieldSpec 4 Standard Resolution spectrometer. This initial data release contains data for samples collected between 2024/03/28 and 2024/11/29, and encompasses a total of 445 samples of 151 species. This includes 1 seed sample of 1 species, 173 flower samples of 78 species, 158 fruit samples of 77 species, 23 bark samples of 22 species, and 90 leaf samples of 40 species.  Data collection is ongoing and this dataset will be expanded in future releases. The goal of this project is to contribute to the basis for automated species identification of woody plants in diverse tropical forests using hyperspectral imaging.  

---------------------
DATA & FILE OVERVIEW
---------------------

## Data Collection
- Location: Barro Colorado Island, Panama
- Instrument: ASD FieldSpec 4 Standard Resolution spectrometer
- Methods: The methods are described in the protocol `ProtocolsSpeciesSpectraBCI_2024-01-20.pdf`.

## Files Included in This Data Package
- `ProtocolsSpeciesSpectraBCI_2025-01-20.pdf`: Detailed protocols used for collecting hyperspectral reflectance data from plant organs on Barro Colorado Island, Panama.
- `ProtocolsSpeciesSpectraBCI_ESP_2025-01-21.pdf`: Detailed protocols, translated into Spanish, used for collecting hyperspectral reflectance data from plant organs on Barro Colorado Island, Panama.
- `hyperspectral_reflectance_BCI.csv`: Hyperspectral reflectance measurements collected from various plant organs on Barro Colorado Island, Panama.
- `README.txt` : Overview of the data package and instructions for usage.
- `Variable_Description.csv : Metadata describing the variables included in the dataset.
- `Categorical_Codebook.csv` : Definitions and explanations for categorical variables used in the dataset.

### Additional Definitions
- Sample: A single collection of tissue or organ taken from a plant to measure on a specific day, typically consisting, for example, of multiple flowers of a given plant (or multiple fruits, etc.) Each sample is assigned a unique SampleID.
- Subsample: A distinct subsample of a sample. Each sample was divided into 5 distinct subsamples (e.g., 5 individual flowers, or 5 groups of flowers for very small flowers, or 5 individual petals of flowers for very large flowers), each of which is measured separately.
- Subview: A particular view of a sample, for example, internal or external view of a capsule, or the aril vs. seed part of a fruit. Many samples have only one subview, others have multiple subviews.
- Measurement: A single measurement of spectral reflectance of a given subsample or white reference using a spectrometer.

## Acknowledgments
Financial support for this research was provided by a 2024 Smithsonian Pathfinder grant to Helene Muller-Landau titled "Building the basis for automated species identification of tropical plants from spectral and laser scanning data."  We gratefully acknowledge the assistance of botanists David Brassfield, Omar Hernandez, and Osvaldo Calderon with plant species identification, and of Yoseline Angel in training the team in the use of the spectrometer and assisting in protocol development. We thank all collaborators and team members who contributed to and provided support for this research.

## Data Usage: This dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). You are free to share, copy, redistribute, remix, transform, and build upon the material for any purpose, including commercial use, provided that you give appropriate credit, include a link to the license (https://creativecommons.org/licenses/by/4.0/), and indicate if any changes were made. 
To cite this dataset, please use the following format: 
Daria Lipsky, Lily Pitcher, Juan Camilo Osorio-Ospina, & Helene C. Muller-Landau. 2024. Hyperspectral Reflectance Data for Flowers, Fruits, Bark, and Leaves of Plants on Barro Colorado Island, Panama. Smithsonian Research Data Repository. [DOI or URL]. Licensed under CC BY 4.0.

