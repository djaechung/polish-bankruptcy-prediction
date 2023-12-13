Finnancial data for Polish companies, used to train and test our team's bankruptcy classifiers

Terminology:
* `csv_result` - original Polish company data
* `<n>year` - number of years into the future bankruptcy is recorded for
* `test` - data split reserved for model testing
* `train` - data split reserved for model training
* `imputed` - missing values are imputed in the data
* `oversampled` - some records of the minority class are duplicated at random to mitigate class imbalance problem
* `undersampled` - some records of the majority class are excluded at random to mitigate class imbalance problem
