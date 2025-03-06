# Metadata Requirements

This page provides an overview of the minimum metadata required for publication on Smithsonian Tropical Data Portal. These requirements are used by the Smithsonian Tropical Data Portal team to review datasets before approval for publication.

Smithsonian Tropical Data Portal’s dataset metadata requirements allow you to fully describe your dataset so that others can more easily find and use relevant data from dataset searches. Metadata for each dataset submitted should meet the guidelines in the description of each field listed below, and metadata completeness will be assessed during the dataset publication process using both automated and manual review workflows. Ensuring that your dataset has complete metadata before publication will expedite the publication process.

Dataset metadata fields marked with a red asterisk (<span style = "color:red">*</span>) are required to submit your dataset. All dataset metadata fields are reviewed using the requirements outlined in the Description of each field.

## Controlled and Prohibited Information

Smithsonian Tropical Data Portal will not accept any datasets that include controlled and prohibited information categories ([SD-118](https://vol.si.edu/download/821SX461LSZXO4OR?u=HC35ZC31NCG95JON)), such as Protected Information (i.e., Personally Identifiable Information [PII] and Sensitive Personally Identifiable Information [SPII]).

### Examples of PII and SPII

- Social Security Number (SSN) or personal Tax Identification Number
- Driver’s license or Government-issued identification number
- Medical information (i.e., a diagnosis or condition)
- Biometric identifiers (e.g., iris scans, retina scans, fingerprints)

See SD-118 for a detailed list of examples.

## Automated Checks

A set of automated checks are performed whenever a dataset is submitted. The results of these checks are compiled into an Assessment Report and used in the review process. Failed automated checks or warnings should be addressed as much as possible by the dataset submitter before requesting publication.

## Step By Step Information 

<div style="display: flex; align-items: flex-start;">
 <div style="margin-right: 50px;">
   <h3>Overview</h3>
   <ul>
     <li><a href="#title">Title<span style = "color:red">*</span></a></li>
     <li><a href="#existing-doi-and-alternative-identifiers">Existing DOI & Alternate Identifiers</a></li>
     <li><a href="#canonical-dataset">Canonical Dataset Identifier</a></li>
     <li><a href="#abstract">Abstract<span style = "color:red">*</span></a></li>
     <li><a href="#keywords">Keywords<span style = "color:red">*</span></a></li>
     <li><a href="#publication-date">Publication Date</a></li>
     <li><a href="#funding">Funding Organization</a></li>
     <li><a href="#usage-rights">Usage Rights<span style = "color:red">*</span></a></li>
   </ul>
 </div>

 <div>
   <h3>People</h3>
   <ul>
     <li><a href="#contact">Contact*</a></li>
     <li><a href="#creators">Creators*</a></li>
     <li><a href="#metadata-contributors">Contributors</a></li>
   </ul>

   <h3>Dates</h3>
   <ul>
     <li><a href="#start-date">Start Date</a></li>
     <li><a href="#end-date">End Date</a></li>
   </ul>

   <h3>Locations</h3>
   <ul>
     <li><a href="#geographic-description">Geographic Description</a></li>
     <li><a href="#bounding-box-coordinates">Bounding Box Coordinates</a></li>
   </ul>

   <h3>Methods</h3>
   <ul>
    <li><a href="#methods-1">Methods</a></li>
 </div>
</div>

# Overview

## Title <span style = "color:red">*</span>  
|                     |                                                                                                                                                                                                                                                                                                                                                                |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                                                                                                                                                                                                      |
| **Description**     | Include a title between 7-20 words long which contains information such as the topic, geographic location, dates, and scale of data. If data is associated with a journal publication, the title may include the journal name.<br><br>Avoid unexplained acronyms or project-specific vocabulary. If there is an existing DOI for the data, use the same title. |
| **Example**         | Raw sapflow and soil moisture data from January 2016-April 2016 in Manaus, Brazil                                                                                                                                                                                                                                                                              |
| **JSON-LD Field**   | `name`                                                                                                                                                                                                                                                                                                                                                         |
| **Automated Check** | **Required:** Dataset title is between 7 and 40 words in length                                                                                                                                                                                                                                                                                                |

## Existing DOI and Alternative Identifiers
|                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Description**     | If this dataset is archived in another location, such as a different data management system, list any additional identifiers that can be used to locate or label the dataset here, enter the DOI or alternate identifier. Identifiers are used to locate the dataset within your project's data management system and can provide pertinent contextual information for users. Ensure the identifier correctly leads to the dataset that you are submitting. |
| **Example**         | http://dx.doi.org/XXXX                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Automated Check** |                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

## Canonical Dataset
|                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Description**     | If this dataset is essentially a duplicate of a version stored elsewhere, provide the ID of the original dataset here. This must be a DOI or URL. Sometimes datasets in the Smithsonian Tropical Data Portal are essentially duplicates of an external dataset that was originally published elsewhere. For example, researchers may want to preserve a copy of a dataset in STDP for posterity or to ensure that the data remains accessible. In such cases, it is more approprite to cite the original dataset rather than the copy. The canonical version is displayed prominently on the dataset landing page, making it easy for users to identify the original dataset and cite it correctly. This avoids issues with misrepresentation and citation confusion. |
| **Example**         | http://dx.doi.org/XXXX   ;      https://datadryad.org/dataset/doi:10.5061/dryad.q2bvq83v4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Automated Check** |

## Abstract <span style = "color:red">*</span> 
|                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Description**     | The abstract should be at least 100 words in length, written in full sentences, and understandable to anyone who has not seen related manuscripts.<br><br>Describe the content of the dataset, and provide all necessary scientific context, avoid unexplained acronyms or project specific terms, and include specific details that promote the reproducibility of your data.<br><br>This may include source data for synthesis work, software necessary to view the related files, ecosystem type involved, or measurement types.<br><br>Include a statement about the purpose for why these data were generated and the research question it is intended to answer. |
| **Example**         | This dataset contains raw output from a data logger connected to 9 sapflow and 5 soil moisture sensors in Manaus, Brazil. The file xxx.dat contains raw data and the metadata file (BR-Ma2_E-fieldlog_20160501.xls) has information on locations where the sensors were installed and other sensor maintenance details. No data processing or QA/QC was done on the raw datasets. Processed data will be uploaded as separate datasets on ESS-DIVE. This research was performed as a part of the NGEE Tropics project, which aims to advance model predictions of tropical forest carbon cycle responses to a changing climate over the 21st Century.                  |
| **Automated Check** | **Required**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

## Keywords <span style = "color:red">*</span> 
|                     |                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | GCMD Keywords OR Free Text                                                                                                                                                                                                                                                                                                                                                                                              |
| **Description**     | Add a minimum of three total keywords or data variables. As you begin typing in the web form field, GCMD controlled vocabulary terms will appear in a dropdown list. Selecting from the GCMD controlled keywords where possible is encouraged but not required. You can also enter your own keywords. Ensure that keyword terms differ from words in the title to increase the findability of your dataset in searches. |
| **Example**         | Earth Science, Land Surface, Soils                                                                                                                                                                                                                                                                                                                                                                                      |
| **Automated Check** | **Required**                                                                                                                                                                                                                                                                                                                                                                                                            |

## Publication Date
|                     |                                                                                                                                                |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | YYYY or YYYY-MM-DD                                                                                                                             |
| **Description**     | Specify a custom date or year when this dataset can be made publicly available. If this is not specified, it will default to the current date. |
| **Example**         | 2025 or 2025-01-01                                                                                                                             |
| **Automated Check** |                                                                                                                                                |

## Funding
|                     |                                                                                                                                 |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                       |
| **Description**     | List the organizations, grants, or anything else that funded the work.                                                          |
| **Example**         | Smithsonian ForestGEO, HSBC Climate Partnership, National Science Foundation. Grant Numbers: 1457279, 1943583, 1951244, 2017949 |
| **Automated Check** |                                                                                                                                 |


## Usage Rights <span style = "color:red">*</span> 
|                     |                                                                                                                                                                                                                                                                      |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Select Choice                                                                                                                                                                                                                                                        |
| **Description**     | Choose how you wish your data to be shared and reused. Creative Commons Attribution (CC BY 4.0) requires that the dataset be cited by anyone using the data. Creative Commons Public Domain (CC BY 1.0) dedicates the data to the public domain without restriction. |
| **Example**         | Select Creative Commons Attribution (CC BY 4.0) or Creative Commons Public Domain (CC BY 1.0)                                                                                                                                                                        |
| **Automated Check** |                                                                                                                                                                                                                                                                      |

# People


## Contact <span style = "color:red">*</span> 
|                     |                                                                                                                                                                                        |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                              |
| **Description**     | List the person who should be contacted by users seeking further information for the data. Only one contact is allowed. Including the ORCID of this individual is strongly encouraged. |
| **Example**         | First name, Last name, Organization, Email, ORCID (strongly encouraged)                                                                                                                |
| **Automated Check** |                                                                                                                                                                                        |

## Creators <span style = "color:red">*</span>
|                     |                                                                                                                                                                                                                                                                                            |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Format**          | Free Text                                                                                                                                                                                                                                                                                  |
| **Description**     | Include the main researchers involved in producing the data such as authors, owners, originators, and principal investigators. List creators in the order they should appear in the dataset citation. One or more creators is required and including email addresses is highly encouraged. |
| **Example**         | First name, Last name, Organization, Email, ORCID (not required for creators)                                                                                                                                                                                                              |
| **Automated Check** |                                                                                                                                                                                                                                                                                            |

## Metadata Contributors
|                     |                                                                                                                                                                                                                                                                   |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                                                                                                         |
| **Description**     | List any additional contributors involved in producing the data. These may include people who assisted in creating the dataset but are not considered authors. Contributors will not appear in the data citation. Including email addresses is highly encouraged. |
| **Example**         | First name, Last name, Organization, Email, ORCID (not required for contributors)                                                                                                                                                                                 |
| **Automated Check** |                                                                                                                                                                                                                                                                   |

# Dates

## Start Date
|                     |                                                           |
| ------------------- | --------------------------------------------------------- |
| **Format**          | YYYY or YYYY-MM-DD                                        |
| **Description**     | Earliest date of data collection included in the dataset. |
| **Example**         | 2025, 2025-01-01                                          |
| **Automated Check** |                                                           |

## End Date
|                     |                                                                                                                   |
| ------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **Format**          | YYYY or YYYY-MM-DD                                                                                                |
| **Description**     | Last date of data collection included in the dataset. This field can be left blank if your dataset is open-ended. |
| **Example**         | 2025, 2025-01-01                                                                                                  |
| **Automated Check** |                                                                                                                   |

# Locations

## Geographic Description
|                     |                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Description**     | A short description of the location(s) where data was collected. This may include the location name, known identifiers if associated with a specific project (e.g., Ameriflux site name), and ecosystem type involved. Multiple geographic descriptions can be added if necessary. A complete geographic description will increase the findability of your dataset, as all terms entered are searchable through the data portal. |
| **Example**         | Br-Ma2, Manaus, Brazil: ZF2 K34 Tower. Eddy covariance site established in 1999 on kilometer 34 of the ZF2 highway. It was later expanded into an atmospheric and soil sampling hub. It is a 1.5m x 2.5 m-section aluminum tower, 50 m tall, on a medium-sized plateau (Araujo et al., 2002).<br><br>OR<br><br>Barro Colorado Island (BCI) in Gatun Lake in central Panama                                                       |
| **Automated Check** |                                                                                                                                                                                                                                                                                                                                                                                                                                  |

## Bounding Box Coordinates
|                     |                                                                                                                                                                                                                                                                                                                                                                              |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Latitude and Longitude in WGS 84 decimal degrees                                                                                                                                                                                                                                                                                                                             |
| **Description**     | Latitude and Longitude of the location(s) this data represent in WGS84 decimal format. Enter only one coordinate pair for a single point and bounding box coordinates for non-point locations. Ensure coordinate accuracy before submitting your dataset. If the data location is better represented by a shape, you may also include a KML or SHP file in the file uploads. |
| **Example**         | Northwest Coordinates [Lat Long]/Southeast Coordinates [Lat Long]                                                                                                                                                                                                                                                                                                            |
| **Automated Check** |                                                                                                                                                                                                                                                                                                                                                                              |

# Methods

## Methods
|                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Format**          | Free Text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Description**     | Methods for a dataset should focus on all aspects of dataset production and should be thorough enough for your work to be reproduced. Include descriptions of the experimental design, laboratory and/or field collection methods (e.g., observations and/or devices used), source data for synthesis studies, data processing, and QA/QC procedures, and known issues or limitations of data where applicable. A complete methods section will improve findability of your data, as all text entered into methods will also be searchable for users through the data portal filters.<br><br>You may provide a citation for any methods used that were published previously, but methods related to data production must still be included. |
| **Example**         | An example of a complete methods section can be viewed at: Conlisk E; Castanha C; Germino M J; Veblen T T; Smith J M; Kueppers L M (2017): Data from: "Declines in low-elevation subalpine tree populations outpace growth in high-elevation populations with warming." Subalpine and Alpine Species Range Shifts with Climate Change: Temperature and Soil Moisture Manipulations to Test Species and Population Responses. doi:10.15485/1730950                                                                                                                                                                                                                                                                                           |
| **Automated Check** |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

