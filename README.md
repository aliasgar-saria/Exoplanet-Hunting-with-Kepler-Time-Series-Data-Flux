This project focuses on exoplanet detection using Kepler-labelled time series data. The primary goal is to develop a reliable K-Nearest Neighbors (KNN) classification model that accurately identifies stars with exoplanets based on their flux data. The project utilizes the Kepler-labelled time series dataset from Kaggle.

The data describe the change in flux (light intensity) of several thousand stars. Each star has a binary label of 2 or 1. 2 indicated that that the star is confirmed to have at least one exoplanet in orbit; some observations are in fact multi-planet systems.

As you can imagine, planets themselves do not emit light, but the stars that they orbit do. If said star is watched over several months or years, there may be a regular 'dimming' of the flux (the light intensity). This is evidence that there may be an orbiting body around the star; such a star could be considered to be a 'candidate' system. Further study of our candidate system, for example by a satellite that captures light at a different wavelength, could solidify the belief that the candidate can in fact be 'confirmed'.


NOTE: Classifier needs work as seen on the final Confusion matrix, will get back to this soon

Data Source: https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data
