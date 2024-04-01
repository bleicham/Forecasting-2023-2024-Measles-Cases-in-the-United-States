# Forecasting 2023-2024 Measles Cases in the United States

This dashboard contains forecasts related to the recent surge of measles cases in the United States. We use a generalized growth model (GGM) to produce all forecasts, assuming normal, Poisson, and negative binomial error structures [1], an auto-regressive integrated moving average model (ARIMA), simple linear regression (SLR), a generalized additive model (GAM), and Facebook's Prophet model (Prophet). [1] contains additional details related to the employed modeling methodology for GGM, and the dashboard found in [2] was used to produce the remaining forecasts. The data displayed in the dashboard and used for all forecasts is obtained each Friday from the Centers for Disease Control and Prevention (CDC) [3]. The dashboard is updated each Friday, and all forecasts are publicly available at [4]. 

Last updated on: March 31st, 2024.

Please email ableichrodt1@student.gsu.edu with all inquiries. 

[1] Chowell, G., Bleichrodt, A., Dahal, S. et al. GrowthPredict: A toolbox and tutorial-based primer for fitting and forecasting growth trajectories using phenomenological growth models. Sci Rep 14, 1630 (2024). https://doi.org/10.1038/s41598-024-51852-8

[2] https://github.com/bleicham/ARIMA-GLM-GAM-Prophet-Beta

[3] https://www.cdc.gov/measles/cases-outbreaks.html

[4] https://github.com/bleicham/Forecasting-2023-2024-Measles-Cases-in-the-United-States
