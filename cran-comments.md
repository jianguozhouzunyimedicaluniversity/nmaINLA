---
title: "cran-comments"
output: html_document
---
## New submission
This is a new submission, since I missed the deadline. In this version I have:

* fixed an issue regarding "if" statement following Kurt Hornik's email.

* updated the description.

## R CMD check results
There is 1 NOTE:

Possibly mis-spelled words in DESCRIPTION:
    Friede (9:142)
    Guenhan (9:123)

These are author names.

## Test environments
* ubuntu (devel and release)
* win-builder (devel and release)
* local OS X install, R 3.6.3



## Resubmission
This is a resubmission. In this version I have:

* change the INLA repository to https://inla.r-inla-download.org/R/stable/ 
following Prof. Ripley's email.

* update the citation.


## Resubmission
This is a resubmission. In this version I have:

* Deleted "necessary usage of INLA" from the DESCRIPTION file
and changed the version to 0.1.1

* change the vignette so that INLA used only conditionally on its availability

## Resubmission
This is a resubmission. In this version I have:

* Changed some wording in the DESCRIPTION file


## Test environments
* ubuntu 16.04, R 3.4.0
* local OS X install, R 3.4.0
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs. 

There was 1 NOTE:

* This is my first submission.

* Suggests or Enhances not in mainstream repositories:

  INLA
  
Availability using Additional_repositories specification:

  INLA   yes   http://www.math.ntnu.no/inla/R/testing

The web address (with full url) is provided in the Description 
of the package.


