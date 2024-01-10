## `rgdal`: Bindings for the 'Geospatial' Data Abstraction Library

Provides bindings to the 'Geospatial' Data Abstraction Library ('GDAL') (>= 1.11.4) and access to projection/transformation operations from the 'PROJ' library. Please note that 'rgdal' was retired 16 October 2023, plan transition to sf/stars/'terra' functions using 'GDAL' and 'PROJ' at your earliest convenience (see <https://r-spatial.org/r/2023/05/15/evolution4.html> and earlier blogs for guidance). Use is made of classes defined in the 'sp' package. Raster and vector map data can be imported into R, and raster and vector 'sp' objects exported. The 'GDAL' and 'PROJ' libraries are external to the package, and, when installing the package from source, must be correctly installed first; it is important that 'GDAL' < 3 be matched with 'PROJ' < 6. From 'rgdal' 1.5-8, installed with to 'GDAL' >=3, 'PROJ' >=6 and 'sp' >= 1.4, coordinate reference systems use 'WKT2_2019' strings, not 'PROJ' strings. 'Windows' and 'macOS' binaries (including 'GDAL', 'PROJ' and their dependencies) are provided on 'CRAN'.

- repository: https://r-forge.r-project.org/projects/rgdal/

- CRAN: (Until October 2023) https://cran.r-project.org/package=rgdal

- maintenance status: archived 16 October 2023.

- documentation status: Was ASDAR, http://rgdal.r-forge.r-project.org/