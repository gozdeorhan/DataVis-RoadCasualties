# Data Visualisation - Road Casualties by Severity

Please use the following link to see my full work (including interactive visuals): https://nbviewer.jupyter.org/github/gozdeorhan/DataVis-RoadCasualties/blob/master/DataVis-RoadCasualties.ipynb

An exploratory data visualisation work, utilizing Road Casualties by Severity dataset which is published by Department for Transport of London.

The dataset is analysed to form insightful research questions and thus prepare the dataset accordingly. Following the pre-processing, a univariate analysis and visualisations have been done. Lastly, in light of research questions, multivariate analysis has been done. It has been observed that some geographical locations, time periods and demographic groups are more prone to casualties.

Following questions were asked throughout the project:
- Are there specific locations prone to casualties?
- Are there specific time periods prone to casualties?
- Are there specific demographic groups prone to casualties?

## Dataset

Dataset was acquired through London Datastore website (https://data.london.gov.uk/dataset) under the name of ‘Road Casualties by Severity’, which is published by Department for Transport. The Road Casualties by Severity data:  (https://data.london.gov.uk/dataset/road-casualties-severity-borough).

The dataset was in .csv format with 12 columns and 13206 records of road incidents.

Easting: Eastward-measured distance. Interval.

Northing: Northward-measured distance. Interval.

Severity_of_casualty: An indicator of severity. Two categories: Serious or Fatal. Ordinal.

Casualty_class: Three different classes. Pedestrian, driver or rider and passenger. Nominal.

Sex: Two categories: Female or male. Nominal.

Age: Exact age of casualty. Not in the format of date of birth, etc. Ratio.

Date: Date of incident. Format: dd/mm/yyyy. Interval.

Day_of_week: Seven categories. Nominal.

Hour_of_day: Twenty-four categories. Ratio.

Local_authority: Thirty-four categories. Nominal.

Vehicle_type: Initially there were twenty-five categories. Aggregated into eleven. Nominal.

Pedestrian_locality: Initially there were twelve categories, but the variable removed from dataframe due to inconsistency. Nominal.
