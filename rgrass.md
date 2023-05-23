## `rgrass`: Interface Between 'GRASS' Geographical Information System and 'R'

An interface between the 'GRASS' geographical information system ('GIS') and 'R', based on starting 'R' from within the 'GRASS' 'GIS' environment, or running a free-standing 'R' session in a temporary 'GRASS' location; the package provides facilities for using all 'GRASS' commands from the 'R' command line. The original interface package for 'GRASS 5' (2000-2010) is described in Bivand (2000) <doi:10.1016/S0098-3004(00)00057-1> and Bivand (2001) <https://www.r-project.org/conferences/DSC-2001/Proceedings/Bivand.pdf>. This was succeeded by 'spgrass6' for 'GRASS 6' (2006-2016) and 'rgrass7' for 'GRASS 7' (2015-present). The 'rgrass' package modernizes the interface for 'GRASS 8' while still permitting the use of 'GRASS 7'.

- repository: https://github.com/rsbivand/rgrass

- CRAN: https://cran.r-project.org/package=rgrass

- maintenance status: small group of active contributors on github, moved from `rgdal` to `terra` for GDAL functionality in 2022. Vulnerable to archiving of `XML` on CRAN.

- documentation status: https://rsbivand.github.io/rgrass/, https://rsbivand.github.io/foss4g_2022/, two vignettes added in 2022.