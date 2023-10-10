# Global-Fitting
Using shared parameter fitting (global fitting) to analyze environmental kinetics data

This repository is intended to show examples of the global fitting approach in the context of environmental kinetics data sets. Global fitting is a type of least-squares regression wherein more than one data set is fit by a model with at least some parameters shared across data sets.

A good description of global fitting can be found in Chapter 11 of H. Motulsky and A. Chrstopoulos's regression manual for GraphPad prism.
https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=13050008933573517309

The scietific graphing package Igor Pro also has a well developed tool for performing global fits.
https://www.wavemetrics.com/products/igorpro

The code in this repository will use python with scipy's curve fitting/optimization routines rather than a particular scientific graphics package.