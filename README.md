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

