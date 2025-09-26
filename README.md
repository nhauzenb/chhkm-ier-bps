### T. Chernis, N. Hauzenberger, F. Huber, G. Koop & J. Mitchell (202x). Predictive Density Combination Using Bayesian Machine Learning, *International Economic Review*, forthcoming.

[**Publication (open access)**.](https://doi.org/10.1111/iere.12759)

[**Online Appendix**.](https://www.dropbox.com/scl/fi/4h95f5roqgvajf86ufl45/CHHKM-IER-OnlineAppendix.pdf?rlkey=kjpxc7aionfgsfckrt6jydv1o&st=z3np70fp&dl=0)

### Data for the two empirical applications. 

In the first application, we combine predictive densities of GDP growth for the euro area (EA), produced by individual professional forecasters participating in the ECB Survey of Professional Forecasters (SPF), with the histograms for each forecaster in the panel, publicly available [here](https://www.ecb.europa.eu/stats/ecb_surveys/survey_of_professional_forecasters/html/all_data.en.html). The sub-folder [`data/ECB-SPF`](./data/ECB-SPF) contains the *csv files* for the EA-SPF vintages.

In the second application, we forecast US inflation using a set of autoregressive distributed lag (ADL) regression models. For the different macroeconomic variables in the ADL regressions, we rely on the popular FRED-QD dataset provided by the *Federal Reserve Bank of St. Louis*, publicly available [here](https://research.stlouisfed.org/econ/mccracken/fred-databases/). The sub-folder [`data/US-FRED`](./data/US-FRED) contains two .rda files: one for the one-step ahead inflation forecasting exercise [`CPIAUCSL_qoq_Q_nhor1.rda`](.data/US-FRED/CPIAUCSL_qoq_Q_nhor1.rda) and one for the four-step-ahead exercise [`CPIAUCSL_qoq_Q_nhor4.rda`](.data/US-FRED/CPIAUCSL_qoq_Q_nhor4.rda). 
