---
permalink: /software/
title: "Software"
seo_title: "Software | Brian Maitner"
excerpt: "R packages developed or maintained by Brian Maitner for accessing and cleaning biodiversity data, species distribution modeling, and research software attribution."
author_profile: true
---

R packages I develop or help maintain. Most are on CRAN and can be installed with `install.packages()`. More code from the lab is on the [Maitner Lab GitHub](https://github.com/MaitnerLab).

## Biodiversity data access

- **BIEN**: tools for accessing the Botanical Information and Ecology Network database: plant occurrences, traits, plots, and range maps. [CRAN](https://cran.r-project.org/package=BIEN) · [GitHub](https://github.com/bmaitner/RBIEN) · [paper](https://doi.org/10.1111/2041-210X.12861)
- **OpenRange**: access open species range maps. [CRAN](https://cran.r-project.org/package=OpenRange) · [GitHub](https://github.com/MaitnerLab/OpenRange)

## Biodiversity data cleaning

R interfaces to the BIEN data-cleaning services:

- **TNRS**: Taxonomic Name Resolution Service, which corrects and standardizes plant names. [CRAN](https://cran.r-project.org/package=TNRS) · [GitHub](https://github.com/EnquistLab/RTNRS)
- **GNRS**: Geographic Name Resolution Service, which standardizes country, state, and county names. [CRAN](https://cran.r-project.org/package=GNRS) · [GitHub](https://github.com/EnquistLab/RGNRS) · [paper](https://doi.org/10.1371/journal.pone.0268162)
- **NSR**: Native Status Resolver, which flags whether a species is native or introduced in a region. [CRAN](https://cran.r-project.org/package=NSR) · [GitHub](https://github.com/EnquistLab/RNSR)
- **GVS**: Geocoordinate Validation Service, which checks occurrence coordinates for common errors. [CRAN](https://cran.r-project.org/package=GVS) · [GitHub](https://github.com/EnquistLab/RGVS)

## Analysis

- **S4DM**: species distribution modeling with small sample sizes. [CRAN](https://cran.r-project.org/package=S4DM) · [GitHub](https://github.com/bmaitner/S4DM) · [paper](https://doi.org/10.1002/ecog.08112)
- **traitstrap**: bootstrapping trait distributions from community data. [CRAN](https://cran.r-project.org/package=traitstrap) · [GitHub](https://github.com/Plant-Functional-Trait-Course/traitstrap) · [paper](https://doi.org/10.1111/2041-210x.14160)

## Open Science

- **citeR**: finds the R packages used in your code so you can cite them. [GitHub](https://github.com/MaitnerLab/citeR)

## Just for fun

- **transformerpalettes**: color palettes inspired by Transformers toys, cartoons, and comics. [CRAN](https://cran.r-project.org/package=transformerpalettes) · [website](https://bmaitner.github.io/transformerpalettes/)
