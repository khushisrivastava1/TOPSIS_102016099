# Topsis Description
This python package can help you to calculate topsis score and corresponding rank in maximum 2-3 lines of code.
# SUBMITTED BY:
KHUSHI SRIVASTAVA

102016099

3CS12
# INSTALLATION
 pip install TOPSIS-KHUSHI-102016099
# import 
from TOPSIS_KHUSHI_102016099 import topsis 
# Usage
Call the Topsis function to generate the csv file in which 1st parameter is your input dataframe, 2nd is weights, 3rd is impacts and last is the name of output csv file. For eg:
topsis("102016099-data.csv","1,2,1,2,1","+,-,+,+,-","102016099-result.csv")
# Constraints
1) Input dataframe with 1st column as model name and rest are it's features.
2) Weights must be commas seperated and in the form of a string.
3) Impacts must be commas seperated and in the form of a string having only positive and negative sign.
4) Input file must contain 3 or more columns
5) First column is the object or variable name
6) From 2nd to last columns contain numeric values only

# Output
1) Result file contains all the columns of input file and two additional columns having the topsis score and the rank

# License
Copyright 2023

Khushi Srivastava

This repository is licensed under the MIT License