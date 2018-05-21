initial import
```python
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
```

read csv and show top 10 entries
```python
speech_csv = pd.read_csv('speeches.csv')
speech_csv.head()
```
