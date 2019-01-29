# ttbarMeasurementCMSDAS


## Setup your environment

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

