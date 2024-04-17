# What is including in the file?
--------------------------------------------------------------

`whakamaua_dashboard.xlsx` - holds the underlying data for each indicator in the whakamaua dashboard.

## Column definitions: 

* `Measure` - the name of the measure the data relates to.
* `MeasureType` - the type of value shown in the Value column. ie Client Contacts, Age-standardised rate etc. 
* `Year` - Year, if includes / then is a financial year, otherwise is calendary year
* `Ethnicity` - Prioritised ethnicity, except for measure 1.3 Unmet need.
* `GeoArea` - Geographic area breakdown - IMPB or total
* `AgeGroup` - Age group breakdowns where this is available
* `VariableName` - Specific topic for sub-groupings related to measures
* `Variable` - underlying aspect of the specific topic noted in VariableName
* `Value` - the number related to the measure type and grouping variables in this row
* `LowerCI` - 95% lower confidence interval of the value where applicable
* `UpperCI` - 95% upper confidence interval of the value where applicable
* `QualityInd` - flag for health survey data quality (1.3 Unmet need)

