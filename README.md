[![Static Badge](https://img.shields.io/badge/DOI-10.3832%2Fifor4868-018?style=flat-square&logo=doi&color=green)](https://doi.org/10.3832/ifor4868-018)
![Static Badge](https://img.shields.io/badge/python-3.12-blue?style=flat-square&logo=Python) ![Static Badge](https://img.shields.io/badge/nextflow-24.10.5-green?style=flat-square&logo=nextflow&color=%230CAE8)




# Stem Xylem Traits in Poplar Genotypes (Populus L.): *additional parameters for selection and breeding*

__Zorić Lana<sup>1</sup>, Pilipović Andrej<sup>2</sup>, Junel Solis<sup>3</sup>, Ramish Bibi<sup>3</sup>, Irina Belaia<sup>3</sup>, Dado Tokic<sup>3</sup>, Pasi Kankaanpää <sup>3</sup>, Davidović Sonja <sup>1</sup>, Karanović Dunja <sup>1</sup>, Luković Jadranka <sup>1</sup>__
[See affiliations](#organizational-affiliations)

*iForest - Biogeosciences and Forestry, Volume 19, Issue 1, Pages 52-60 (2026)
doi: https://doi.org/10.3832/ifor4868-018*  

### Abstract
Selection programs targeting Populus species are primary oriented towards the formation of fast-growing genotypes. This study aimed to explore the anatomical features of stem xylem and vessel traits in Populus clones, offering valuable parameters for guiding future selection and breeding efforts. To achieve this objective, cross-sections of one-year-old shoots of two-year-old trees were analyzed using light microscopy. Measurements of xylem parameters were performed using automated image analysis, and theoretical hydraulic conductance (Kh), vulnerability index (Vi) and vessel grouping index were calculated.  

Based on the findings, we propose that stem anatomical characteristics related to xylem and vessel traits can serve as valuable tools in selecting poplar clones with enhanced productivity, water transport efficiency, drought or cavitation resistance. A significant correlation was found between shot anatomical properties and Kh and Vi. From an anatomical perspective, breeding efforts aimed at increased growth should prioritize the development of clones with a higher xylem proportion (xylem/phloem ratio), large-lumen vessels, a greater proportion of solitary vessels, and a reduced percentage of grouped vessels. Conversely, breeding for drought-tolerant clones and those with enhanced resistance to cavitation should focus on clones with a higher number of small-lumen vessels, a greater percentage of grouped vessels, more vessel groups, and vessel groups containing a higher number of vessels. The anatomical approach described here represents an efficient and accessible method for assessing the growth potential and cavitation and drought resistance of poplar trees.  

__Key words__: *cavitation, stem anatomy, vessels, water conductivity*

<sub><sup>1</sup>University of Novi Sad, Faculty of Sciences, Department of Biology and Ecology, Novi Sad, Serbia  
<sup>2</sup>University of Minnesota Duluth, Natural Research Institute, Duluth, MN, USA  
<sup>3</sup>Turku BioImaging, Åbo Akademi University and University of Turku, Turku, Finland</sub>  

<p align="left" style="display: flex; justify-content: center; gap: 25px;">
  <img src="https://novisad2022.rs/wp-content/uploads/2021/06/univerzitet-u-novom-sadu-297x300.png" alt="University of Novi Sad Logo" style="height: 75px; width: auto;">
  <img src="https://apps.utu.fi/media/logo/UTU_logo_EN_RGB.png" alt="University of Turku Logo" style="height: 75px; width: auto;">
  <img src="https://www.abo.fi/wp-content/uploads/2019/09/AboAkademi-logo_black.png" alt="Åbo Akademi Logo" style="height: 75px; width: auto;">
</p>
  


## Data sources
Raw image data - [Download](https://a3s.fi/swift/v1/2024-lana-zoric-populus-data/raw-data.zip)  
StarDist model and weights - [Download](https://a3s.fi/swift/v1/2024-lana-zoric-populus-data/stardist-final.zip)

<sub>Object storage for this project is hosted by the [Allas]([https://csc.fi](https://docs.csc.fi/data/Allas/)) service of the Centre for Scientific Computing (*Tieteen tietotekniikan keskus Oy*) in Finland.<sub>

## Workflow run
```
nextflow run main.nf -c nextflow.config.local -resume
```
This workflow was built using [Nextflow](https://nextflow.io) and therefore requires a UNIX-based operating system such as Linux or MacOS. On Microsoft Windows, [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) is a good option.

Download and extract the raw image data. Create a local copy of `nextflow.config.example` e.g. `nextflow.config.local` and modify it to fit your local parameters. Setup a Python 3.12 environment based on `./environment.yml`. Execute `nextflow` within the Python environment.
