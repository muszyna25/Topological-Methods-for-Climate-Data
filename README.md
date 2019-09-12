# Topological-Methods-for-Climate-Data
Working prototype of topological &amp; machine learning method for AGU book chapter, Wiley.

Chapter: "Topological Methods for Pattern Detection in Climate Data."

Grzegorz Muszynski (1,2), Vitaliy Kurlin (1), Dmitriy Morozov (2), Michael Wehner (2), Karthik Kashinath (2), and Prabhat (2)

1) Department of Computer Science, University of Liverpool, Liverpool, L69 3BX, United Kingdom
2) Lawrence Berkeley National Laboratory, Berkeley, California, 94720, United States

------------------------------------------------------------------------------------------------------------------------------
Instructions:

I) TDA_source_code.cxx contains a C++ code for computing topological feature descriptors (tracking sizes of connected components) from snapshots of climate model outputs in a threshold-free way. This code works only with TECA software (https://github.com/LBL-EESA/TECA). TECA includes all necessary external packages and libraries for this implementation.

II) Preprocessing_TECA_output.py preprocesses output files of topological feature extraction in I).

III) ML_source_code.py contains all code to train and test Support Vector Machine (SVM) classifier in python scikit-learn  (https://scikit-learn.org/stable/modules/svm.html). It requires an installion of python3.5/3.6 and all necessary modules.

