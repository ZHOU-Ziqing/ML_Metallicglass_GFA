Files in ML_Metallic glass_GFA are the source code of the work "Rational design of chemically complex metallic glasses by hybrid modeling guided machine learning" (https://www.nature.com/articles/s41524-021-00607-4)
The files including:
1. descriptors.zip: the calculation of descriptors
2. Classificationmodels.mat: the training results of classification models
3. Regressionmodels, including ANN.zip, RQGPR.mat, ExpGPR.mat, SqExpGPR.mat, GSVM.mat, and RF.mat: the training results of regression models
4. Analysis.zip: the data analysis

descriptors running procedure:
1. Run lagrange.m to get the expression of atomic size descirptors (the results are already provided in Meanvalue.mat).
2. Run featurescalculate to get the values of 10 descriptors (only column 3-10 are applied in the work, colum 1-2 are not used).
