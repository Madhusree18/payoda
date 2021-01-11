# payoda
The dataset contains 20 different features from 155 patients with chronic liver disease.
pandas , numpy, matplotlib libraries are imported.
Data preprocessing is done by calculating shape,description of the data.
Missing Values are handled and replaced using median imputation method.
Particularly, the feature protime is deleted because around 155 records 70 are missing values. there is no use of having that feature for futher observation so it get rejected.
Duplicate records were checked.
To know about the outliers , boxplot is used.
Correlation plot is performed to know the relationship between the variables. according to this, relation between histology and bilirubin are higher.
Using this correlation plot,feature selection is done for futher plots.
