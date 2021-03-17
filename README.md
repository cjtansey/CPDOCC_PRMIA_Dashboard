# CPDOCC_PRMIA_Dashboard
Dashboard for PRMIA's risk management challenge 2021


The dashboard is designed to offer comprehensive risk management metrics.

In order to adjust the VaR estimates, select the drop-down menu to the right of the Risk Assessment Title. Then choose the type of VaR estimate you would like
Historical uses the historical distribution and VaR.
Monte Carlo uses a monte carlo simulation of 10,000 to find tha VaR. The simulation uses a student t copula to model dependency.
Exponential Weighted Average is a variant of the historical simulation that applies a greater rate to more recent observations. The lambda is set to a standard .94.

To adjust the alpha level, select the dropdown menu to the left the Risk Assessment title and select your desired alpha level. The simulations do not reset when variables are changed.

To change the currency pair for the portfolio overview, go to the menu to the right of "Portfolio Overview" and select the currency pair you are interested in.

All of the data can be read in directly from .csv's, so the application is flexible for any data requirements.

To generate a report: Press the "Generate Report" button in the top right corner. This report contains all of the same metrics in the dashboard, except for the portfolio overview tables. The report's output is a .pdf file.
