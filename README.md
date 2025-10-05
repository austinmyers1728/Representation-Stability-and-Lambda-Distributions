# Representation-Stability-and-Lambda-Distributions
This code computes the stable multiplicities of irreducible representations in configuration spaces of algebraic curves, as well as the cohomology with coefficients in local systems for higher dimensional varieties.
#=====================================================================

There is a folder for each curve/variety, and within each folder, there is code that computes the: 

- Laurent series whose coefficients are the multiplicities,
- Rational function which can be expanded out to the above Laurent series
- List of multiplicities for 0<i<20

The each file of code is entirely self-contained, so it can simply be copy-pasted into SAGE to run.

Each file also has a "file writer," which is used to output a json file which can be used to easily read off the LaTeX code in HTML.
