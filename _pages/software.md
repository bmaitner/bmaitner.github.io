---
permalink: /software/
title: "Software"
seo_title: "Software | Brian Maitner"
excerpt: "R packages developed or maintained by Brian Maitner for accessing and cleaning biodiversity data, species distribution modeling, and research software attribution."
author_profile: true
---

R packages I develop or help maintain: 13 on CRAN, with more than 631,000 downloads from the RStudio CRAN mirror as of November 2026. CRAN packages install with `install.packages()`. More code from the lab is on the [Maitner Lab GitHub](https://github.com/MaitnerLab).

## Biodiversity data access

- **BIEN**: tools for accessing the Botanical Information and Ecology Network database: plant occurrences, traits, plots, and range maps. [CRAN](https://cran.r-project.org/package=BIEN) · [GitHub](https://github.com/bmaitner/RBIEN) · [paper](https://doi.org/10.1111/2041-210X.12861)
- **OpenRange**: access open species range maps. [CRAN](https://cran.r-project.org/package=OpenRange) · [GitHub](https://github.com/MaitnerLab/OpenRange)
- **BIENapi**: API access to the BIEN database (in development). [GitHub](https://github.com/EnquistLab/RBIENapi)
- **occCite** (co-author): querying biodiversity occurrence data with reproducible citation of sources. [CRAN](https://cran.r-project.org/package=occCite) · [paper](https://doi.org/10.1111/ecog.05618)

## Biodiversity data cleaning

R interfaces to the BIEN data-cleaning services:

- **TNRS**: Taxonomic Name Resolution Service, which corrects and standardizes plant names. [CRAN](https://cran.r-project.org/package=TNRS) · [GitHub](https://github.com/EnquistLab/RTNRS)
- **GNRS**: Geographic Name Resolution Service, which standardizes country, state, and county names. [CRAN](https://cran.r-project.org/package=GNRS) · [GitHub](https://github.com/EnquistLab/RGNRS) · [paper](https://doi.org/10.1371/journal.pone.0268162)
- **NSR**: Native Status Resolver, which flags whether a species is native or introduced in a region. [CRAN](https://cran.r-project.org/package=NSR) · [GitHub](https://github.com/EnquistLab/RNSR)
- **GVS**: Geocoordinate Validation Service, which checks occurrence coordinates for common errors. [CRAN](https://cran.r-project.org/package=GVS) · [GitHub](https://github.com/EnquistLab/RGVS)

## Analysis

- **S4DM**: species distribution modeling with small sample sizes. [CRAN](https://cran.r-project.org/package=S4DM) · [GitHub](https://github.com/bmaitner/S4DM) · [paper](https://doi.org/10.1002/ecog.08112)
- **traitstrap** (co-author): bootstrapping trait distributions from community data. [CRAN](https://cran.r-project.org/package=traitstrap) · [GitHub](https://github.com/Plant-Functional-Trait-Course/traitstrap) · [paper](https://doi.org/10.1111/2041-210x.14160)
- **occTest** (co-author): characterizing and filtering species occurrence data. [GitHub](https://github.com/pepbioalerts/occTest)
- **wallace** (contributor): a modular platform for reproducible modeling of species niches and distributions. [CRAN](https://cran.r-project.org/package=wallace) · [paper](https://doi.org/10.1111/ecog.06547)

## Open Science

- **citeR**: finds the R packages used in your code so you can cite them (in development). [GitHub](https://github.com/MaitnerLab/citeR)
- **rangeModelMetadata** (co-author): metadata standards for documenting species range models. [CRAN](https://cran.r-project.org/package=rangeModelMetadata) · [paper](https://doi.org/10.1111/geb.12993)

## Color palettes

Color palettes for scientific figures, with ggplot2 scales and helpers that screen palettes for color-blind-safe, sequential, or diverging use.

- **glyospalettes**: palettes drawn from Glyos toy colorways. [CRAN](https://cran.r-project.org/package=glyospalettes)
- **transformerpalettes**: palettes drawn from Transformers toys, cartoons, and comics. [CRAN](https://cran.r-project.org/package=transformerpalettes) · [website](https://bmaitner.github.io/transformerpalettes/)
