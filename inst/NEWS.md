# planar 1.6 (28/02/2016)

## LAYOUT

* NEWS -> inst/NEWS.md

## NEW FEATURES

* merged Tamm package

## LOW LEVEL

* removed Rcpp modules
* switched to Rcpp Attributes
* exported cpp functions start with cpp_

# planar 1.5.2 (16/08/2014)

## NEW FEATURES

* full field profile under gaussian beam illumination (reflection and transmission)

* new functions multilayerfull and multilayer_field calculating internal field for a given incident field

## USER VISIBLE CHANGES:

* slight changes to the interface of field_profile

## LOW LEVEL:

* rewrote the gaussian beam code to use multilayer matrix transfer method

* link to cubature at c++ level to perform the gaussian beam integration


# planar 1.5 (16/12/2013)

## USER VISIBLE CHANGES:

* initial version of gaussian beam calculations (single layer, incomplete)

* removed demos (see wiki instead)

* more consistent variable names and output

* angles are in radians, distances in nanometres

## BUG FIX:

* (Rcpp::)function namespace issues with some c++ compilers

## LOW LEVEL:

* tests

* vignettes moved to vignettes/

planar 1.3.1

## BUG FIX:

* fixed missing prefactor in transmission coefficient when incident / outgoing media were not vacuum

# planar 1.3 (not released)

## USER VISIBLE CHANGES:

* cleanup function names

* depends on dielectric (0.2.2)

## NEW FUNCTIONALITY:

* added gaussian module for gaussian beam calculations

## DOCUMENTATION:

* vignettes using knitr

* cleanup wiki and demos

# planar 1.2.5 (2013-01-06)

## DOCUMENTATION:

* wiki added

* cleanup demos

## INTERNAL CHANGES:

* misc updates to clean up package

## USER VISIBLE CHANGES:

* units are in nm

# planar 1.2.4 (2012-09-19)

## BUG FIX:

* ggplot2 compatibility

# planar 1.2.3 (2012-07-14)

## BUG FIX:

* fixed demos

# planar 1.2.2 (2012-07-05)

## BUG FIX:

* fixed demos, vignette, and misc code arguments

# planar 1.2.1 (2012-05-15) 

## BUG FIX:

* fixed bugs for ggplot2-0.9.1

# planar 1.2 (2012-02-07) 

## BUG FIX:

* fixed bugs for ggplot2-0.9.0

# planar 1.1	(2011-07-30)

## BUG FIX:

* revert to plain ascii text

# planar 1.0	(27/07/2011)

* Initial CRAN release