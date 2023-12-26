# DataPrepKit

DataPrepKit is a Python class designed to simplify common data preparation tasks when working with tabular data using the Pandas library. It provides functionalities for reading data from various file formats, handling missing values, generating data summaries, and encoding categorical data.

## Features

1. **Data Reading:**
   - Read data from different file formats such as CSV, Excel, and JSON.

2. **Handling Missing Values:**
   - Remove or impute missing values based on specified strategies.

3. **Data Summary:**
   - Generate statistical summaries for specified columns, including mean, variance, standard deviation, and quartiles.

4. **Categorical Data Encoding:**
   - Encode categorical variables into numerical representations.

## Usage

```python
from DataPrepKit import DataPrepKit
# Example Usage
data_prepper = DataPrepKit('data.csv')
data_prepper.handling_missing_values(columns=['Age', 'Salary'], strategy='mean')
summary = data_prepper.data_summary('Salary')
encoding_df = data_prepper.categorical_data_encoding('Gender')
```

## Dependencies
**Pandas**

**NumPy**
## Author
**Seyf Eddine**


## Electro Pi Task
This project was created as part of the [Electropi Python Programming Foundation](https://electropi.ai/lessons/python-programming-foundation) course.

