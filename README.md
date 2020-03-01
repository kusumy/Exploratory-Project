
**Implentation and Analysis of Support Vector Regression, Twin SVR and Weighted Twin SVR**

**Support Vector Regression**

Creating the instance of the Support Vector regression from `sklearn` and then testing it on the artificial dataset.

Its implementation, evaluation of the result and the visualization of the data set and predicted labels by the algorithm can be found in `SVR.ipynb`.

**Twin Support Vector Regression**

Creating the class of Twin Support Vector regression as the child class of `BaseEstimator` and `RegressorMixin` of `sklearn.base`

The class of `TwinSVR` is implemented in `twinsvr.py`

Using the object of `TwinSVR` we would test the algorithm on the same artificial dataset used in SVR.

Its implementation, evaluation of the result and the visualization of the data set and predicted labels by the algorithm can be found in `TwinSVR.ipynb`.

**Weighted Twin Support Vector Regression**

Creating the class of Weighted Twin Support Vector regression as the child class of `BaseEstimator` and `RegressorMixin` of `sklearn.base`

The class of `WeightedTSVR` is implemented in `wtwinsvr.py`

Using the object of `WeightedTSVR` we would test the algorithm on the same artificial dataset used in SVR.

Its implementation, evaluation of the result and the visualization of the data set and predicted labels by the algorithm can be found in `WeightedTSVR.ipynb`.

**Report**

Report on the math and comparison of the the three algorithms on the artifical dataset. It can be found in `Report.pdf`.
