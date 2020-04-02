# Medication2RxNorm

Automatically Normalize Medication Records using the standard name, code, and properties from RxNorm.

Byunggu Yu, Ph.D.

April 2, 2020

Your medication records in your csv file are augmented with clean medication concept names and standard Rx codes and all other properties from RxNorm through approximate name search. All added fields are named with name_prefix "M2RxNorm_" (you can change this) in the output csv file.

Input: Your own csv file containing medication records with medication names (e.g., zocor 10 mg) from arbitrary sources. Note: the first line of the csv file must be comma-separated column (field) names.

Output: -m2rxnorm.csv containing clean standard names and various standard codes (e.g., NDA code) and all other properties from RxNorm. All added fields are named with prefix "M2RxNorm_" in the output csv file.
