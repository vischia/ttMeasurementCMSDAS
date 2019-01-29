# ttbarMeasurementCMSDAS


In the current exercise you will use two tools for statistical analysis that are of common usage in High Energy Physics.
The objective of the current exercise is to learn how to measure the production cross section of top quark pairs at sqrt(s)=5TeV; the cross section is the *observable* (the physical quantity) that we want to determine from our data obtaining a *measurement*, e.g. stating that the cross section is XXX (*value*) +/- YYY (*uncertainty*) pb. The same problem is referred to in statistics as *parameter estimation*; the cross section is the *parameter*, which in nature has a specific value (or range of values), the *true value*. We obtain an *estimate* of the parameter when we quote a certain value (*point estimate*) and a range of values around it (*interval*).

## References on statistical methods

A good overview of statistics at the LHC can be found in [Practical Statistics for the LHC by Kyle Cranmer](https://arxiv.org/abs/1503.07622), whereas a more complete treatment of the statistics commonly used at the LHC can be found in the nice [Statistical Methods for Experimental Physics by Fred James](https://www.amazon.com/Statistical-Methods-Experimental-Physics-2Nd/dp/9812705279). Both references are from particle physicists, so the language should not be too obscure. If you are interested in the statisticians' take on the topic---which I recommend---you can read the very nice book [Statistical Inference by Casella and Berger](https://www.amazon.fr/Statistical-Inference-George-Casella/dp/0495391875/).

## Setup your environment

Higgs combination tool documentation: 
Link to combine documentation

## Build a datacard, given a table

Signal region, counting only, one or two uncertainties

Determine the cross section of ttbar production separately in the mu+jets (examples/mujets.txt) and the el+jets final state (examples/eljets.txt), and plot the corresponding likelihoods

Combine the two measurements making use of BLUE (Best Linear Unbiased Estimator)
Determine the cross section for ttbar production my making use simultaneously of the two final states using combine; combineCards.py
Compare the precision of the two determinations (BLUE combination and combine simultaneous fit)

### From now on, only combine will be used

## Diagnostics
- It is desirable to avoid looking at the data before having frozen all the details of the analysis: use the Asimov dataset
- The Impacts as diagnostic tool
- Splitting uncertainties

# Multiple signal regions

Two regions (e+jets, mu+jets)

## Constraining backgrounds using a control regions

Example reasonable CR
Example bad CR
Compare results


## Shape datacard

Build the card, given shape in some variable (signal, backgrounds)
Add constraints from CR
Add bin-by-bin statistical uncertainties

