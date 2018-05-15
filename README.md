# OpenFOAM-2.4.x

This is my personal fork of OpenFOAM-2.4.x with the following changes:

## Changelog

* Added support for Intel Xeon Phi KNL architecture (GccKNL)
* Added support to GCC 6.x: Backported nullObject class from OpenFOAM 3.0.x. 
This fixes weird segfaults on renumberMesh or recontructPar, etc when using this gcc version.
