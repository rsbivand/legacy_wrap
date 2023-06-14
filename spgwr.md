## `spgwr`: Geographically Weighted Regression

Functions for computing geographically weighted regressions are provided, based on work by Chris Brunsdon, Martin Charlton and Stewart Fotheringham.

### Update 2023-06-15

- 0.6-36 published on CRAN

- repository https://github.com/rsbivand/spgwr

- documentation https://rsbivand.github.io/spgwr/

- prospective new maintainer contacted

### Initial

- repository: https://r-forge.r-project.org/projects/rspatial/

- CRAN: https://cran.r-project.org/package=spgwr

- maintenance status: Probably to be archived - does not have to go when retiring packages are archived, as it conditions on their presence, but note startup message:
> NOTE: This package does not constitute approval of GWR as a method of spatial analysis; see example(gwr)

Could be deprecated pointing to `GWmodel`, 4 reverse imports. `gwer` will fail when `maptools` is archived and the maintainer email bounces; email sent 2023-05-23:
> gwer, GWLelast, mgwrsar, NSAE vulnerable to archiving of spgwr

> Please consider how you would like to handle the archiving of spgwr, which you use in your packages. spgwr suggests retiring r-spatial packages maptools and rgdal, and while your packages would (mostly, gwer does not and I have attempted to warn the maintainer) survive the archiving of maptools, rgdal and rgeos in October 2023, I am not motivated to maintain spgwr further. I am open to handing over to another maintainer, or to archiving the package. I'm interested in hearing your reactions.

`pkgapi` 2023-05-24 shows no use of code by reverse import packages, so most likely only used in documentation.

- documentation status: http://rspatial.r-forge.r-project.org/spgwr/, vignette taken from ASDAR 1ed.
