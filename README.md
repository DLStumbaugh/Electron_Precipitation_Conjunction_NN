# Electron_Precipitation_Conjunction_NN
A conjunction-trained artificial neural network (ANN) that requires low-Earth-orbit electron fluxes, L and MLT, and AE measurements as sole inputs

# Python Dependencies
1. Python >= 3.11.7
2. numpy >= 1.24.3
3. matplotlib >= 3.8.0
4. scikit-learn >= 1.3.0
5. pandas >= 2.1.4
6. notebook >=7.0.6
7. scipy >=1.11.0

# Data
1. The RBSP/MagEIS ‘release 4 (rel04)’ level 3 data are publicly accessible at https://rbspgway.jhuapl.edu/.
2. The POES/MetOp data are publicly accessible at https://www.ngdc.noaa.gov/stp/satellite/poes/dataaccess.html.
3. The OMNI data are publicly accessible at https://cdaweb.gsfc.nasa.gov/.
4. For the POES20172018.mat file, visit https://zenodo.org/records/14058506

# Code Structure
File: ElectronPrecipitationML.ipynb

1. Create and format a data frame (from ConjunctionData.mat)
2. Establish train and test data
3. Complete GridSearchCV and Train MLPRegressor ANN
5. May 2017- Mar 2018 Testing (from POES20172018.mat)
6. Plot error metrics

# Correspondence
Dominique Stumbaugh (PhD student), University of California, Los Angeles. dstumbaugh@ucla.edu
