# Modeling-NMR-Derived-T2-Porosity-using-Conventional-Open-Hole-Logs

Porosity in complex lithologies, particularly shale reservoirs, is difficult to measure using conventional (Quad-Combo) well logs. NMR-derived porosity is considered the total porosity "gold standard', as it is measured exclusive of matrix and mineralogy. However, due to NMR tools existing as relatively new technology, and the extra expense in logging runs and rig time, most wells lack these data. The ability to accurately model NMR-derived porosity using conventional logs is of great value to minimize error in petrophysical models.

Here is a case study using the University 43-15 (42-383-37393) vertical pilot drilled by Devon Energy 2012. Delivered curves used directly as feature variables include the bulk of the Quad-Combo suite (GR, LLD, LLS, NPHI, DPHI, PE, DTC) with Spectral Gamma (POTA, URAN, THOR). A deterministic 4 mineral mineralogic model (QTZ, CARB, VCLAY, TOC) was created and calibrated to spectroscopy values from the GEM log. Cutoffs were applied to mineralogic model to create a basic facies curve using 4 lithofacies (Organic shale, Shale, Carb, Sand). Facies were used as categorial features.

These data were used to model for NMR-Derived Porosity from the Haliburton MRIL log. ML modeling algorithms included OLS, Ridge Regression, LASSO Regression, Elastic Net Regression, KNN Neighbors, Random Forest and Gradient Boost. The choice model was a Random Forest model with adjusted hyperparameters to reduce overfitting, and resulted in a root-means-squared-error of 1.48%.


Included Work and Data: 
  1.  Four LAS files (Triple Combo, Dipole Sonic, GEM, MRIL)
  2.  Notebook 
  3.  Presentation summary of results 
