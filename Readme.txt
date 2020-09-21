Research Aptitude Test:

Topic: Information-Theoretic Variable Selection and Network Inference from Microarray Data
Notation:
MI= Mutual Information

Algorithms: 
1- MASSIVE (Matrix of Average SubSubset Information for Variable Elimination)
2- MRNet (Minimum Redundancy NETwork) for Network Inference

Tools Used:
1- Core i7-7500u
2- Python 3.7.9 (64-bit)
3- VSCode
4- The following AI/ML toolkits were used
•	Scikit-learn
•	Tensorflow
•	Keras
•	Pandas
•	Numpy
•	Matplotlib
5- WINDOWS 10-OS

DataSet:
The original dataset in its raw form can be downloaded from 
https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original)

Proceedure:
The source code is available in the file project.py
The original dataset was downloaded from the link.
This data set was then cleaned in order to perform analysis. 
The mutual information was calculated using scikit-learn and pands.
After the calculation of mutual information, d=3 i.e. no of input variables for the model were chosen.
Since the choice of d is based on priori knowledge so d=3 was chosen randomly for ease of calculations.
The best 3 variables were chosen and again MI was calculated, as dropping variables direclty affects MI.
Once the Xs subset of X-input variables was chosen, the next step was to calculate PREEST for the given dataset.
The calcuations upto PREEST can be perfomed using the given sourcecode.

CSV files info:
The file named OGData contains the original dataset.
The file named CData contains the Cleaned dataset.
XS.csv is used to recaulacute the MI after selecting best three variables.
XS0, XS1 and XS2 are used for PREEST calculations of respective indices.
