<!-- README.md is generated from README.Rmd. Please edit that file -->

# [AFSC RACE Groundfish and Shellfish Survey Public Data](https://github.com/afsc-gap-products/gap_public_data/) <img src="https://avatars.githubusercontent.com/u/91760178?s=96&amp;v=4" alt="Logo." align="right" width="139" height="139"/>

## This code is primarily maintained by:

**Emily Markowitz** (Emily.Markowitz AT noaa.gov;
[@EmilyMarkowitz-NOAA](https://github.com/EmilyMarkowitz-NOAA))  
Research Fisheries Biologist  
*Bering Sea Groundfish Survey Team*

Alaska Fisheries Science Center,  
National Marine Fisheries Service,  
National Oceanic and Atmospheric Administration,  
Seattle, WA 98195

[![](https://img.shields.io/github/last-commit/afsc-gap-products/gap_public_data.svg)](https://github.com/afsc-gap-products/gap_public_data/commits/main)

> The code in this repository is regularly being updated and improved.
> Please refer to
> [releases](https://github.com/afsc-gap-products/gap_public_data//releases)
> for finalized products and project milestones. *The FOSS dataset is
> only updated once a year and may be slightly behind the GitHub
> repository.* This metadata is regarding scripts and data last ran and
> pushed to the AFSC oracle on **April 24, 2023**.

## Table of contents

> - [*Cite this data*](#cite-this-data)
> - [*Access the data*](#access-the-data)
> - [*Collabrators and data users*](#collabrators-and-data-users)
>   - [*Bottom trawl surveys and
>     regions*](#bottom-trawl-surveys-and-regions)
> - [*Metadata*](#metadata)
>   - [*Data description (short)*](#data-description-(short))
>   - [*Data description (long)*](#data-description-(long))
>   - [*Relevant technical
>     memorandums*](#relevant-technical-memorandums)
>   - [*User resources*](#user-resources)
>   - [*Access constraints*](#access-constraints)
>   - [*Column-level metadata*](#column-level-metadata)

# Cite this data

Use the below bibtext
[citation](https://github.com/afsc-gap-products/gap_public_data//blob/main/CITATION.bib),
as cited in our group’s [citation
repository](https://github.com/afsc-gap-products/citations/blob/main/cite/bibliography.bib)
for citing the data from this data portal (NOAA Fisheries Alaska
Fisheries Science Center, 2023). Add “note = {Accessed: mm/dd/yyyy}” to
append the day this data was accessed.

    ## @misc{FOSSAFSCData,
    ##    author = {{NOAA Fisheries Alaska Fisheries Science Center}},
    ##    year = {2023}, 
    ##    title = {Fisheries One Stop Shop Public Data: RACE Division Bottom Trawl Survey Data Query},
    ##    howpublished = {https://www.fisheries.noaa.gov/foss},
    ##    publisher = {{U.S. Dep. Commer.}},
    ##    copyright = {Public Domain} 
    ## }

# Access the data

Here are a few resources made by our scientists in house and keen
contributors:

- [General
  information](https://afsc-gap-products.github.io/gap_public_data/)
- [Access data via the FOSS Interactive
  Platform](https://afsc-gap-products.github.io/gap_public_data/access-foss.html)
- [Access data via the API in
  R](https://afsc-gap-products.github.io/gap_public_data/access-api-r.html)
- [Access data via the API in
  Python](https://afsc-gap-products.github.io/gap_public_data/access-api-py.html);
  by Sam Pottinger (<sam.pottinger@berkeley.edu>)
- [Access data via the AFSC Oracle Database (AFSC
  only)](https://afsc-gap-products.github.io/gap_public_data/access-afsc-oracle-r.html)

# Collabrators and data users

Below are a few packages and products currently using this data. If you
have developed a product, performed an analysis, or exhibited this data
in any way, reach out so we can showcase your hard work.

**[NOAA Fisheries Distribution Mapping and Analysis
Portal](https://apps-st.fisheries.noaa.gov/dismap)**; [NOAA Fisheries
Office of Science and
Technology](https://www.fisheries.noaa.gov/contact/office-science-and-technology)

**[Pull data with python](https://pyafscgap.org/) and explore the
[in-browser visualization tool](https://app.pyafscgap.org/'). Reference
their [example Python
notebook](https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb)**;
[The Eric and Wendy Schmidt Center for Data Science and the Environment
at UC Berkeley](https://dse.berkeley.edu/), including
<sam.pottinger@berkeley.edu>, <ccmartinez@berkeley.edu>,
<gzarpellon@berkeley.edu>, and <kkoy@berkeley.edu>.

## Bottom trawl surveys and regions

![](Z:/Projects/gap_public_data/img/survey_plot.png)

- **Aleutian Islands (AI)** (Von Szalay and Raring, 2020)
  - Triennial (1990s)/Biennial since 2000 in even years
  - Modified Index-Stratified Random of Successful Stations Survey
    Design
- **Eastern Bering Sea Slope (BSS)** (Hoff, 2016)
  - Intermittent (funding dependent)
  - Modified Index-Stratified Random of Successful Stations Survey
    Design
- **Eastern Bering Sea Shelf (EBS)** (Markowitz et al., 2022)
  - Annual
  - Fixed stations at center of 20 x 20 nm grid
- **Gulf of Alaska (GOA)** (Von Szalay and Raring, 2018)
  - Triennial (1990s)/Biennial since 2001 in odd years
  - Stratified Random Survey Design
- **Northern Bering Sea (NBS)** (Markowitz et al., 2022)
  - Biennial/Annual
  - Fixed stations at center of 20 x 20 nm grid

# Metadata

## Data description (short)

This dataset includes zero-filled (presence and absence) observations
and catch-per-unit-effort (CPUE) estimates for all identified species at
for index stations by the Resource Assessment and Conservation
Engineering Division (RACE) Groundfish Assessment Program (GAP) of the
Alaska Fisheries Science Center (AFSC). There are no legal restrictions
on access to the data. The data from this dataset are shared on the
Fisheries One Stop Stop (FOSS) platform
(<https://www.fisheries.noaa.gov/foss/>). The GitHub repository for the
scripts that created this code can be found at
<https://github.com/afsc-gap-products/gap_public_data>. For more
information about codes used in the tables, please refer to the survey
code books
(<https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual>).
These data were last updated April 24, 2023.

## Data description (long)

The Resource Assessment and Conservation Engineering Division (RACE)
Groundfish Assessment Program (GAP) of the Alaska Fisheries Science
Center (AFSC) conducts fisheries-independent bottom trawl surveys to
monitor the condition of the demersal fish and crab stocks of Alaska.
These data are developed to describe the temporal distribution and
abundance of commercially and ecologically important groundfish species,
examine the changes in the species composition of the fauna over time
and space, and describe the physical environment of the groundfish
habitat.

There are no legal restrictions on access to the data. They reside in
the public domain and can be freely distributed. Users must read and
fully comprehend the metadata prior to use. Data should not be used
beyond the limits of the source scale. Acknowledgement of NOAA, as the
source from which these data were obtained, in any publications and/or
other representations of these data, is suggested. These data are
compiled and approved annually after each summer survey season. The data
from previous years are unlikely to change substantially once published.

These data are zero-filled (presence and absence) observations from
surveys conducted on fishing vessels. These surveys monitor trends in
distribution and abundance of groundfish, crab, and bottom-dwelling
species in Alaska’s marine ecosystems. These data include estimates of
catch-per-unit-effort (CPUE) for all identified species for index
stations. Some survey data are excluded, such as non-standard stations,
surveys completed in earlier years using different/non-standard gear,
and special tows and non-standard data collections.

Though not included in the public data, these surveys also collect
oceanographic and environmental data, and biological data such as
length, weight, stomach contents (to learn more about diet), otoliths
(fish ear bones to learn about age), and tissue samples for genetic
analysis, all of which can be shared upon special request. Also not
included in the public data are estimated biomass (average total weight
of all fish and crabs sampled) of crabs and groundfish that support the
creation of annual stock assessments.

## Relevant technical memorandums

<div id="refs" class="references csl-bib-body hanging-indent"
line-spacing="2">

<div id="ref-RN979" class="csl-entry">

Hoff, G. R. (2016). *Results of the 2016 eastern Bering Sea upper
continental slope survey of groundfishes and invertebrate resources*
(NOAA Tech. Memo. NOAA-AFSC-339). U.S. Dep. Commer.
<https://doi.org/10.7289/V5/TM-AFSC-339>

</div>

<div id="ref-2021NEBS2022" class="csl-entry">

Markowitz, E. H., Dawson, E. J., Charriere, N. E., Prohaska, B. K.,
Rohan, S. K., Stevenson, D. E., and Britt, L. L. (2022). *Results of the
2021 eastern and northern Bering Sea continental shelf bottom trawl
survey of groundfish and invertebrate fauna* (NOAA Tech. Memo.
NMFS-F/SPO-452; p. 227). U.S. Dep. Commer.
<https://doi.org/10.25923/g1ny-y360>

</div>

<div id="ref-FOSSAFSCData" class="csl-entry">

NOAA Fisheries Alaska Fisheries Science Center. (2023). *Fisheries one
stop shop public data: RACE division bottom trawl survey data query*.
https://www.fisheries.noaa.gov/foss; U.S. Dep. Commer.

</div>

<div id="ref-cb2021" class="csl-entry">

Resource Assessment, A. F. S. C. (U.S.)., and Division, C. E. (2021).
*Groundfish survey data codes and forms*.
https://doi.org/<https://doi.org/10.25923/kp5e-1g02>

</div>

<div id="ref-GOA2018" class="csl-entry">

Von Szalay, P. G., and Raring, N. W. (2018). *Data report: 2017 <span
class="nocase">Gulf of Alaska</span> bottom trawl survey* (NOAA Tech.
Memo. NMFS-AFSC-374). U.S. Dep. Commer.
https://doi.org/[http://doi.org/10.7289/V5/TM-AFSC-374
](http://doi.org/10.7289/V5/TM-AFSC-374 )

</div>

<div id="ref-AI2018" class="csl-entry">

Von Szalay, P. G., and Raring, N. W. (2020). *Data report: 2018 Aleutian
Islands bottom trawl survey* (NOAA Tech. Memo. NMFS-AFSC-409). U.S. Dep.
Commer. https://doi.org/<https://doi.org/10.25923/qe5v-fz70>

</div>

</div>

## User resources

- [AFSC RACE Groundfish Assessment Program
  (GAP)](https://www.fisheries.noaa.gov/contact/groundfish-assessment-program).
- [AFSC Resource Assessment and Conservation Engineering Division
  (RACE)](https://www.fisheries.noaa.gov/about/resource-assessment-and-conservation-engineering-division).
- For more information about codes used in the tables, please refer to
  the [survey code
  books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual)
  (Resource Assessment and Division, 2021).
- Find [past
  reports](https://www.fisheries.noaa.gov/resource/publication-database/noaa-institutional-repository)
  about these surveys.
- [GitHub
  repository](https://github.com/afsc-gap-products/gap_public_data/).
- Learn more about other [research surveys conducted at
  AFSC](https://www.fisheries.noaa.gov/alaska/ecosystems/alaska-fish-research-surveys).

## Access constraints

**There are no legal restrictions on access to the data. They reside in
the public domain and can be freely distributed.**

**User Constraints:** Users must read and fully comprehend the metadata
prior to use. Data should not be used beyond the limits of the source
scale. Acknowledgement of AFSC Groundfish Assessment Program, as the
source from which these data were obtained, in any publications and/or
other representations of these data, is suggested.

**Address:** Alaska Fisheries Science Center (AFSC) National Oceanic and
Atmospheric Administration (NOAA)  
Resource Assessment and Conservation Engineering Division (RACE)  
Groundfish Assessment Program (GAP) 7600 Sand Point Way, N.E. bldg. 4  
Seattle, WA 98115 USA

**General questions and more specific data requests** can be sent to
<afsc.gap.metadata@noaa.gov> or submitted as an [issue on our GitHub
Organization](https://github.com/afsc-gap-products/data-requests). The
version of this data used for stock assessments can be found through the
Alaska Fisheries Information Network (AKFIN). For questions about the
eastern Bering Sea surveys, contact Duane Stevenson
(<Duane.Stevenson@noaa.gov>). For questions about the Gulf of Alaska or
Aleutian Islands surveys, contact Ned Laman (<Ned.Laman@noaa.gov>). For
questions specifically about crab data in any region, contact Mike
Litzow (<Mike.Litzow@noaa.gov>), the Shellfish Assessment Program lead.

For questions, comments, and concerns specifically about the [Fisheries
One Stop Shop (FOSS)](https://www.fisheries.noaa.gov/foss) platform,
please contact us using the Comments page on the
[FOSS](https://www.fisheries.noaa.gov/foss) webpage.

## Column-level metadata

| Column name           | Column name (long)                                       | Units                            | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|:----------------------|:---------------------------------------------------------|:---------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| year                  | Year                                                     | year                             | Year the survey was conducted in.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| srvy                  | Survey                                                   | text abbreviated                 | Abbreviated survey names. The column ‘srvy’ is associated with the ‘survey’ and ‘survey_id’ columns. Northern Bering Sea (NBS), Southeastern Bering Sea (EBS), Bering Sea Slope (BSS), Gulf of Alaska (GOA), Aleutian Islands (AI).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| survey                | Survey Name                                              | text                             | Name and description of survey. The column ‘survey’ is associated with the ‘srvy’ and ‘survey_id’ columns.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| survey_definition_id  | Survey ID                                                | ID code                          | This number uniquely identifies a survey. Name and description of survey. The column ‘survey_id’ is associated with the ‘srvy’ and ‘survey’ columns. For a complete list of surveys, review the [code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| cruise                | Cruise ID                                                | ID code                          | This is a six-digit number identifying the cruise number of the form: YYYY99 (where YYYY = year of the cruise; 99 = 2-digit number and is sequential; 01 denotes the first cruise that vessel made in this year, 02 is the second, etc.).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| haul                  | Haul Number                                              | ID code                          | This number uniquely identifies a sampling event (haul) within a cruise. It is a sequential number, in chronological order of occurrence.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| hauljoin              | Haul ID                                                  | ID code                          | This is a unique numeric identifier assigned to each (vessel, cruise, and haul) combination.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| stratum               | Stratum ID                                               | ID code                          | RACE database statistical area for analyzing data. Strata were designed using bathymetry and other geographic and habitat-related elements. The strata are unique to each survey series. Stratum of value 0 indicates experimental tows.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| station               | Station ID                                               | ID code                          | Alpha-numeric designation for the station established in the design of a survey.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| vessel_name           | Vessel Name                                              | text                             | Name of the vessel used to collect data for that haul. The column ‘vessel_name’ is associated with the ‘vessel_id’ column. Note that it is possible for a vessel to have a new name but the same vessel id number. For a complete list of vessel ID codes, review the [code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| vessel_id             | Vessel ID                                                | ID code                          | ID number of the vessel used to collect data for that haul. The column ‘vessel_id’ is associated with the ‘vessel_name’ column. Note that it is possible for a vessel to have a new name but the same vessel id number. For a complete list of vessel ID codes, review the [code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| date_time             | Date and Time of Haul                                    | MM/DD/YYYY HH::MM                | The date (MM/DD/YYYY) and time (HH:MM) of the beginning of the haul.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| latitude_dd_start     | Start Latitude (decimal degrees)                         | decimal degrees                  | Latitude (one hundred thousandth of a decimal degree) of the start of the haul.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| longitude_dd_start    | Start Longitude (decimal degrees)                        | decimal degrees                  | Longitude (one hundred thousandth of a decimal degree) of the start of the haul.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| latitude_dd_end       | End Latitude (decimal degrees)                           | decimal degrees                  | Latitude (one hundred thousandth of a decimal degree) of the end of the haul.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| longitude_dd_end      | End Longitude (decimal degrees)                          | decimal degrees                  | Longitude (one hundred thousandth of a decimal degree) of the end of the haul.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| species_code          | Taxon Code                                               | ID code                          | The species code of the organism associated with the ‘common_name’ and ‘scientific_name’ columns. For a complete species list, review the [code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| itis                  | ITIS Taxonomic Serial Number                             | ID code                          | Species code as identified in the Integrated Taxonomic Information System (<https://itis.gov/>).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| worms                 | World Register of Marine Species Taxonomic Serial Number | ID code                          | Species code as identified in the World Register of Marine Species (WoRMS) (<https://www.marinespecies.org/>).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| common_name           | Taxon Common Name                                        | text                             | The common name of the marine organism associated with the ‘scientific_name’ and ‘species_code’ columns. For a complete species list, review the [code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| scientific_name       | Taxon Scientific Name                                    | text                             | The scientific name of the organism associated with the ‘common_name’ and ‘species_code’ columns. For a complete taxon list, review the [code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| taxon_confidence      | Taxon Confidence Rating                                  | category                         | Confidence in the ability of the survey team to correctly identify the taxon to the specified level, based solely on identification skill (e.g., not likelihood of a taxon being caught at that station on a location-by-location basis). Quality codes follow: **‘High’**: High confidence and consistency. Taxonomy is stable and reliable at this level, and field identification characteristics are well known and reliable. **‘Moderate’**: Moderate confidence. Taxonomy may be questionable at this level, or field identification characteristics may be variable and difficult to assess consistently. **‘Low’**: Low confidence. Taxonomy is incompletely known, or reliable field identification characteristics are unknown. Documentation: [Species identification confidence in the eastern Bering Sea shelf survey (1982-2008)](http://apps-afsc.fisheries.noaa.gov/Publications/ProcRpt/PR2009-04.pdf), [Species identification confidence in the eastern Bering Sea slope survey (1976-2010)](http://apps-afsc.fisheries.noaa.gov/Publications/ProcRpt/PR2014-05.pdf), and [Species identification confidence in the Gulf of Alaska and Aleutian Islands surveys (1980-2011)](http://apps-afsc.fisheries.noaa.gov/Publications/ProcRpt/PR2014-01.pdf). |
| cpue_kgkm2            | Weight CPUE (kg/km<sup>2</sup>)                          | kilograms per kilometers squared | Catch weight (kilograms) divided by area (squared kilometers) swept by the net.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| cpue_nokm2            | Number CPUE (no/km<sup>2</sup>)                          | count per kilometers squared     | Catch number (in number of organisms) per area (squared kilometers) swept by the net.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| weight_kg             | Taxon Weight (kg)                                        | kilograms                        | Weight (thousandths of a kilogram) of individuals in a haul by taxon.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| count                 | Taxon Count                                              | count, whole number resolution   | Total number of individuals caught in haul by taxon, represented in whole numbers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| bottom_temperature_c  | Bottom Temperature (Degrees Celsius)                     | degrees Celsius                  | Bottom temperature (tenths of a degree Celsius); NA indicates removed or missing values.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| surface_temperature_c | Surface Temperature (Degrees Celsius)                    | degrees Celsius                  | Surface temperature (tenths of a degree Celsius); NA indicates removed or missing values.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| depth_m               | Depth (m)                                                | degrees Celsius                  | Bottom depth (tenths of a meter).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| distance_fished_km    | Distance Fished (km)                                     | degrees Celsius                  | Distance the net fished (thousandths of kilometers).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| net_width_m           | Net Width (m)                                            | meters                           | Measured or estimated distance (meters) between wingtips of the trawl.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| net_height_m          | Net Height (m)                                           | meters                           | Measured or estimated distance (meters) between footrope and headrope of the trawl.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| area_swept_km2        | Area Swept (km)                                          | kilometers                       | The area the net covered while the net was fishing (kilometers squared), defined as the distance fished times the net width.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| duration_hr           | Tow Duration (decimal hr)                                | hours, tenths resolution         | This is the elapsed time between start and end of a haul (decimal hours).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| performance           | Haul Performance Code                                    | category                         | This denotes what, if any, issues arose during the haul. For more information, review the [code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
