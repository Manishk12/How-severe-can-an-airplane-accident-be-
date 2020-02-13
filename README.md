# How-severe-can-an-airplane-accident-be-
Predict the severity of airplane accidents caused due to various factors.
# Data:
## The dataset comprises 3 files: 

Train.csv: [10000 x 12 excluding the headers] contains Training data
Test.csv: [2500 x 11 excluding the headers] contains Test data
sample_submission.csv: contains a sample of the format in which the Results.csv needs to be
# Data Description:

##Columns	Description
-Accident_ID	unique id assigned to each row\
-Accident_Type_Code	the type of accident (factor, not numeric)\
-Cabin_Temperature	the last recorded temperature before the incident, measured in degrees fahrenheit\
-Turbulence_In_gforces	the recorded/estimated turbulence experienced during the accident\
-Control_Metric	an estimation of how much control the pilot had during the incident given the factors at play\
-Total_Safety_Complaints	number of complaints from mechanics prior to the accident\
-Days_Since_Inspection	how long the plane went without inspection before the incident\
-Safety_Score	a measure of how safe the plane was deemed to be\
-Violations	number of violations that the aircraft received during inspections\
-Severity\	
a description (4 level factor) on the severity of the crash [Target]

