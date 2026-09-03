# Package index

## Model fitting and tuning

Functions for fitting empirical Bayes models, tuning hyperparameters,
and preparing contingency-table inputs.

- [`pvEBayes()`](https://docs.ropensci.org/pvEBayes/reference/pvEBayes.md)
  : Fit a general-gamma, GPS, K-gamma, KM or efron model for a
  contingency table.
- [`pvEBayes_tune()`](https://docs.ropensci.org/pvEBayes/reference/pvEBayes_tune.md)
  : Select hyperparameter and obtain the optimal general-gamma or efron
  model based on AIC and BIC
- [`estimate_null_expected_count()`](https://docs.ropensci.org/pvEBayes/reference/estimate_null_expected_count.md)
  : Estimate expected null baseline count based on reference row and
  column
- [`generate_contin_table()`](https://docs.ropensci.org/pvEBayes/reference/generate_contin_table.md)
  : Generate random contingency tables based on a reference table
  embedded signals,and possibly with zero inflation

## Posterior inference and extraction

Functions for generating posterior draws, computing posterior signal
probabilities, and extracting fitted models.

- [`posterior_draws()`](https://docs.ropensci.org/pvEBayes/reference/posterior_draws.md)
  : Generate posterior draws for each AE-drug combination
- [`get_posterior_prob()`](https://docs.ropensci.org/pvEBayes/reference/get_posterior_prob.md)
  : Obtain posterior probability of being a signal
- [`extract_all_fitted_models()`](https://docs.ropensci.org/pvEBayes/reference/extract_all_fitted_models.md)
  : Extract all fitted models from a tuned pvEBayes Object

## Model summaries and comparison

S3 methods and helper functions for summarizing fitted pvEBayes objects
and comparing fitted models.

- [`summary(`*`<pvEBayes>`*`)`](https://docs.ropensci.org/pvEBayes/reference/summary.pvEBayes.md)
  : Summary method for a pvEBayes object
- [`summary_table_pvEBayes()`](https://docs.ropensci.org/pvEBayes/reference/summary_table_pvEBayes.md)
  : Obtain a summary table for a pvEBayes object
- [`print(`*`<pvEBayes>`*`)`](https://docs.ropensci.org/pvEBayes/reference/print.pvEBayes.md)
  : Print method for a pvEBayes object
- [`logLik(`*`<pvEBayes>`*`)`](https://docs.ropensci.org/pvEBayes/reference/logLik.pvEBayes.md)
  : Extract log marginal likelihood for a pvEBayes object
- [`AIC(`*`<pvEBayes>`*`)`](https://docs.ropensci.org/pvEBayes/reference/AIC.pvEBayes.md)
  : Obtain Akaike Information Criterion (AIC) for a pvEBayes object
- [`BIC(`*`<pvEBayes>`*`)`](https://docs.ropensci.org/pvEBayes/reference/BIC.pvEBayes.md)
  : Obtain Bayesian Information Criterion (BIC) for a pvEBayes object

## Visualization

Functions for visualizing fitted pvEBayes models, posterior draws, and
posterior signal probabilities.

- [`plot(`*`<pvEBayes>`*`)`](https://docs.ropensci.org/pvEBayes/reference/plot.pvEBayes.md)
  : Plotting method for a pvEBayes object
- [`eyeplot_pvEBayes()`](https://docs.ropensci.org/pvEBayes/reference/eyeplot_pvEBayes.md)
  : Generate an eyeplot showing the distribution of posterior draws for
  selected drugs and adverse events
- [`heatmap_pvEBayes()`](https://docs.ropensci.org/pvEBayes/reference/heatmap_pvEBayes.md)
  : Generate a heatmap plot visualizing posterior probabilities for
  selected drugs and adverse events

## Example datasets

Example spontaneous reporting system datasets included with the package.

- [`statin2025`](https://docs.ropensci.org/pvEBayes/reference/statin2025.md)
  : FDA statin dataset with 5119 adverse events
- [`statin2025_44`](https://docs.ropensci.org/pvEBayes/reference/statin2025_44.md)
  : FDA statin dataset with 44 adverse events
- [`statin42`](https://docs.ropensci.org/pvEBayes/reference/statin42.md)
  : FDA statin dataset with 42 adverse events
- [`gbca2025`](https://docs.ropensci.org/pvEBayes/reference/gbca2025.md)
  : FDA GBCA dataset with 1328 adverse events
- [`gbca2025_69`](https://docs.ropensci.org/pvEBayes/reference/gbca2025_69.md)
  : FDA GBCA dataset with 69 adverse events
- [`faers_opioid_mental`](https://docs.ropensci.org/pvEBayes/reference/faers_opioid_mental.md)
  : FDA opioid dataset with 243 mental-related adverse events
- [`vigi_opioid_mental`](https://docs.ropensci.org/pvEBayes/reference/vigi_opioid_mental.md)
  : VigiBase opioid dataset with 100 mental-related adverse events

## Package overview

- [`pvEBayes-package`](https://docs.ropensci.org/pvEBayes/reference/pvEBayes-package.md)
  : A suite of empirical Bayes methods to use in pharmacovigilance.
