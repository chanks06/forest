# forest
ML task in python to predict forest type based on spectral data 

## dataset citation: 
Johnson,Brian. (2015). Forest type mapping. UCI Machine Learning Repository. https://doi.org/10.24432/C5QP56.

"This data set contains training and testing data from a remote sensing study which mapped different forest types based on their spectral characteristics at visible-to-near infrared wavelengths, using ASTER satellite imagery. The output (forest type map) can be used to identify and/or quantify the ecosystem services (e.g. carbon storage, erosion protection) provided by the forest."

## metadata: 
**Class**: 's' ('Sugi' forest), 'h' ('Hinoki' forest), 'd' ('Mixed deciduous' forest), 'o' ('Other' non-forest land)

**b1 - b9**: ASTER image bands containing spectral information in the green, red, and near infrared wavelengths for three dates (Sept. 26, 2010; March 19, 2011; May 08, 2011.

**pred_minus_obs_S_b1 - pred_minus_obs_S_b9**: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the 's' class (b1-b9).

**pred_minus_obs_H_b1 - pred_minus_obs_H_b9**: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the 'h' class (b1-b9).
