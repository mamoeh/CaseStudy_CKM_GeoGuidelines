Code for Chapter 6 of 'Guidelines for Statistical Disclosure Control Methods Applied on Geo-Referenced Data'

The R code can be run to replicate the case study 'Population grids with the Cell Key Method'

Run in order:

01ckm_prepare_data.R

- download source data
- create artificial micro data for use in 02ckm_protect_and_analyse.R

02ckm_protect_and_analyse.R

- create population grids from artificial micro data and assess small counts risk
- apply Cell Key Method for protection
- calculate a collection of information loss measures

functions_ckm_raster.R and functions_infoloss_raster.R are not run directly, but sourced in 02ckm_protect_and_analyse.R; they contains helper functions for using the Cell Key Method on population grids and implementing information loss measures.

Contact: Martin Möhler (martin.moehler@destatis.de)
