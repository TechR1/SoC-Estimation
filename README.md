# SoC-Estimation using FNN Model

##Intro

We explored the use of DL Model to estimate SoC and found it to give results of better accuracy than traditional approaches like Kalmann Filter, Coulomb counting and SoC - OCV Curves used widely.

## Model

We use 75k data points collected from cycling 32Ah NMC Pouch cells under various ambient conditions(temperature and pressure) and discharge rates to capture the real life performance of the cell over a wide range of conditions.

## Result

The resultant gives an RMSE of 0.5%, outperforming the current industry standard of using Kalmann filter.

## Applications

With range anxiety being one of the major challenges faced by the EV industry in it's booming stages, the need for an accurate method for estimation of the SoC of the battery pack is crucial, both for reliability of the vehicle itself and for improving the life and safety of the battery pack itself.
