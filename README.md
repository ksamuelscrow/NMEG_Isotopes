# NMEG Isotopes
## By: Kimberly Samuels-Crow<sup>1</sup>, Emma Reich<sup>1</sup>, Kiona Ogle<sup>1,2,3</sup>, Marcy Litvak<sup>4</sup>, John Bradford<sup>5</sup>, Daniel Schlaepfer<sup>5</sup>

### Affiliations

<sup>1</sup> School of Informatics, Computing, and Cyber Systems, Northern Arizona University, Flagstaff, AZ 86011
<sup>2</sup> Department of Biological Sciences, Northern Arizona University, Flagstaff, AZ 86011
<sup>3</sup> Center for Ecosystem Science and Society, Northern Arizona University, Flagstaff, AZ 86011
<sup>4</sup> Department of Biology, University of New Mexico, Albuquerque, NM 87131
<sup>5</sup> Southwest Biological Research Center, US Geological Survey, Flagstaff, AZ 86001

## Overview

This repository contains isotope data (δ<sup>2</sup>H [δD] and δ<sup>18</sup>O) from water extracted from stems and soil collected at New Mexico Elevation Gradient sites in 2019 and 2021.

## 1. Methods

### 1.1. Field Methods 

### *1.1.1. Plant Characterization*

We collected stems and soil from a subset of [NMEG sites](https://www.litvaklab.org/new-mexico-elevation-gradient.html): a creosote shrubland (US-Ses) and piñon-juniper woodland (US-Mpj) sampled in October 2019 and June 2021, juniper savannah (US-Wjs) sampled in June 2021, and ponderosa pine forest (US-Vcp) sampled in 2019. We measured the sampled plants at US-Ses, US-Wjs, and US-Mpj in 2021. We used a diameter tape to measure diameter at ground level (DGL) of piñon and juniper trees. Since many of the juniper trees were multi-stem, we selected the largest stem to measure. DGL measurements were taken within 10 cm of the ground. We used a laser range finder to measure the height and canopy dimensions of piñon and juniper. We first measured the vertical distance to the base of the tree, then the vertical distance to the top of the canopy, and then took the difference between the top and base of the tree. For canopy dimensions, we positioned a laser "target" at the edge of the canopy and measured the horizontal distande. We measured the height and canopy dimensions of creosote shrubs using a tape.

### *1.1.2. Stem and Soil Sample Collection*

Stems and soil were collected using methods described in [Samuels-Crow et al. (2023) ](https://www.frontiersin.org/articles/10.3389/ffgc.2023.1116786/full), but we provide some basic details here. 

At each site, we selected 5 plants from each of the dominant woody species (i.e., 5 creosote [*Larrea tridentata* (LATR)] at US-Ses, 5 single-seed juniper [*Juniperus monosperma* (JUMO)] at US-Wjs and US-Mpj, 5 piñon trees [*Pinus edulis* (PIED)] at US-Mpj, and 5 ponderosa pine trees [*Pinus ponderosa* (PIPO)] at US-Vcp. We characterized each sampled plant and took 3 mid-canopy stems for xylem water extraction. For tree or shrub number 1 for each species at each site, we kept the stems separate to evaluate within-tree variability. We pooled the 3 stems for each of the other 4 plants for a total of 7 stem samples per species per site.

We used an unlined soil core sampler to collect soil samples from multiple soil depths adjacent to each of the focal plants. We transfered soil from the core sampler to a large ziploc immediately and homogenized the sample before filling the sample vial. We dug separate soil pits at each site to characterize soil texture.

The sites are located in semiarid ecosystems, so we took great care to minimize evaporation during isotope sample collection. We placed samples in screw-top Wheaton glass vials (24-mL) and immediately sealed them with parafilm before putting them in a cooler filled with dry ice in the field. We stored all samples in a chest freezer located in a cold room until analyzed. 

### 1.2. Lab Methods

### *1.2.1. 2019 Lab Methods*

Samples collected in 2019 were prepared and analyzed using methods described in [Samuels-Crow et al. (2023) ](https://www.frontiersin.org/articles/10.3389/ffgc.2023.1116786/full). We cryogenically extracted water from stem and soil samples on a vacuum line, adding activated charcoal as needed to remove organic compounds, especially in piñon stem water. All soil and stem samples were analyzed on a Picarro L2140-*i* triple isotope analyzer in Northern Arizona University's (NAU) Arizona Climate and Ecosystems (ACE) Isotope Laboratory. We used in-house calibration standards that span values from −142.65 to 1.3‰ (δ<sup>2</sup>H) and −18.74 to −0.09‰ (δ18O) to calculate stretching values ([Sharp, 2017](https://digitalrepository.unm.edu/unm_oer/1/)). See Table 1 for more information. We used deionized tap water to monitor instrument drift. The in-house standards were calibrated to international standards on a DELTA plus XL mass spectrometer.

**Table 1. Isotopic Values for Calibration and Drift Standards (2019)**
| Standard Name | Accepted δ<sup>18</sup>O | Accepted δ<sup>2</sup>H | Standard Type |
|---------------|-----------------|----------------|---------------|
| Kona | -0.09 | 1.3| Calibration |
| Iceland | -7.8 | -51.12 | Calibration |
| Alaska | -18.74 | -142.65 | Calibration |
| DI Water (Flagstaff Tap)| -11.42 | -81.19 | Drift |

There was no systematic drift during sample analysis, and reported values were corrected based on calibration standards.

### *1.2.2. 2021 Lab Methods*

NAU's cryogemic extraction line was unavailable in 2021, so samples collected in 2021 were prepared and analyzed at [University of Wyoming's Stable Isotope Facility](https://www.uwyo.edu/sif/index.html) (UWyoSIF). Water was cryogenically extracted from stems and soil using standard methods. Samples were analyzed using a Temperature Conversion Elemental Analyzer (TC/EA) coupled to a Thermo Delta Plus Isotope Ratio Mass Spectrometer (IRMS). UWyoSIF staff used 2 in-house calibration standards and a drift standard (See Table 2).

**Table 2. Isotopic Values for Calibration and Drift Standards (2021)**
| Standard Name | Accepted δ<sup>18</sup>O | Accepted δ<sup>2</sup>H | Standard Type |
|---------------|-----------------|----------------|---------------|
| UWSIF 301 | -3.5 | -14.4 | Calibration |
| UWSIF 302 | -19.6 | -151.7 | Calibration |
| UWSIF 303 | -15.4 | -114.5 | Drift |

Again, there was no systematic drift during sample analysis, and reported values were corrected based on calibration standards.

## 2. Data Files in Repository

This repository includes (1) "NMEGIsotopeData.csv," which contains δD and δ<sup>18</sup>O results from stem and soil water collected in 2019 and 2021, and (2) "PlantChar.csv," which includes complementary data that contributed to site charactewrization. The results shown in file 1 are calibrated based on standards as described in section 1.2 above.

**Table 3. Column Headers for NMEGIsotopeData.csv file**
| Column Name | Explanation |
|-------------|-------------|
| Vial Number | number for field vial |
| Soil or Stem | Identifies the sample type |
| SampleYear | 2019 or 2021 |
| SampleDate | Date sample was collected |
| Site | NMEG site name |
| Plant | plant number where stem or soil sample was taken |
| soil max depth (cm) | maximum depth for the soil sample interval in cm |
| stem rep or pooled | 3 stems were collected per plant and either analyzed separately or pooled |
| δD | δ<sup>2</sup>H results in per mil |
| δ<sup>18</sup>O | δ<sup>18</sup>O results in per mil |
| Notes | Any quality control notes |

**Table 4. Soil Depths sampled**

| soil max depth (cm) | soil depth interval | sampling year
|---------------------|--------------------------|----------|
| 0 | surface | 2019 |
| 5 | 0-5 cm | 2019 |
| 10 | 0-10 cm | 2021 |
| 15 | 5-15 cm | 2019 |
| 20 | 10-20 cm | 2021 |
| 25 | 15-25 cm | 2019 |
| 30 | 20-30 cm | 2021 |
| 35 | 25-35 cm | 2019 |
| 40 | 30-40 cm | 2021 |
| 50 | 40-50 cm | 2021 |
| 60 | 50-60 cm | 2021 |

Plant characteristics are recorded in the file PlantChar.csv.

**Table 5. Column headers for PlantChar.csv file**

| Column Name | Explanation |
|-------------|-------------|
| Site | NMEG site name |
| Species | species abbreviation (see section 1.1.2 |
| Plant | plant number where stem or soil sample was taken |
| Lat | Latitude in decimal degrees (datum WGS84) |
| Lon | Longitude in decimal degrees (datum WGS84) |
| Base of tree (m) | vertical distance from laser range finder to base of tree |
| Top of tree (m) | vertical distance from laser range finder to top of canopy |
| N-S Canopy dimension (m) | canopy width in north-south direction |
| E-W Canopy dimension (m) | canopy width in north-south direction |
| % Live canopy | estimated percent living canopy |
| DGL (cm) | diameter at ground level |

## 3. Acknowledgements

We thank the several people assisted with sample collection (Mikael Schlumpf, Rachel Auer, Devon Fisher-Chavez, and the rest of the University of New Mexico technician team) and analysis (Jamie Brown, Phiyen Nguyen, Hannah Russell, and Aleisha Lerma). 

## 4. Funding Source

Funding for this data collection came from NSF Award 1834699 (Collaborative Research: Ecohydrological controls on evapotranspiration across a semiarid elevation gradient).
