# Flight-Fare-Prediction
## Overview
The following project predicts Flight Fares using Machine Learning. The Flight Fares for 4 Sources and 5 Destinations are analyzed and then predicted using **Random Forest Regression**.

## Methodology
### Libraries Used
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

```

### PreProcessing
* Extracted Hour of the day from Arriva Date and Departure Date.
* Converted Duration from 'Hour+Min' to 'Min'
* One hot encoding for `Airline`, `Source` and `Destination` variable.

### Feature Selection and Modelling.
* Random Forest regressor is used to select features based on feature importance.
* `Grid Search CV` is used for hyperparameter tuing.

### Results
* `MAE` = `1165.606162629916`
* `MSE` = `4062650.6911608884`
* `RMSE` = `2015.6018186042818`
* `R2 Score` = `0.8117443234361064`

