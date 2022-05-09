# Code and Analysis for "Loss of endangered frugivores from seed dispersal networks generates steep coextinction cascades" manuscript

* AUTHORS 
Therese Lamperty1* and Berry J. Brosi1	
1. Department of Biology, University of Washington, Life Sciences Building, 3747 W Stevens Way NE, Seattle, WA 98195, United States 
*Correspondence: jtl28@uw.edu

* a brief description of where the data are from
*       - Data are from the Bello et al 2017 frugivory dataset found here: https://doi.org/10.1002/ecy.1818
* a brief description of what the analysis is getting at 
*       - Our analysis looks at records of presence/absence of an interaction between fruiting plants and frugivorous animals to create a binary, bipartite seed dispersal network. We then simulate difference loss scenarios to examine the relative importance of endangered frugivores to network robustness-to-coextinctions.

**File structure:

* the **main project folder** contains:
    + R project file ("Atlantic_Forest_Seed_Dispersal_Network.Rproj") this contains the project and all related analyses
    + Rmarkdown file ("Atlantic_Forest_Seed_Dispersal_Network.Rmd") this is the primary analysis file
    + Rmarkdown html report ("Atlantic_Forest_Seed_Dispersal_Network.html") Latest Rmarkdown report showing code output and analysis summary
    + .gitignore (automatic; don't mess)
    + .DS_Store (automatic; don't mess)

* **data-in subfolder** contains data files needed to import to run project:
    + "veg_1992_ibge" folder - just download whole folder and dont mess - it contains the shape files for Brazil's different ecological regions; the code will use this data in delineating where (in which ecoregion) the observation data in the Bello dataset where taken based on the Bello et al data coordinates
    + "ATLANTIC_frugivory_full.og.csv" This is the original observation data publicly available by Bello et al here: https://doi.org/10.1002/ecy.1818
* **data-out subfolder** this is empty, just leave alone
* **results subfolder** this one is empty, but I might use later
* **plots subfolder** has saved plots from the analysis
