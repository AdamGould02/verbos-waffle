import pandas as pd
import numpy as np
%matplotlib inline
import matplotlib.pyplot as plt



df = pd.read_csv("311.csv", low_memory = False)

potholes=df.query('REQUEST_TYPE == "Potholes"')['NEIGHBORHOOD']

potholes.value_counts().tail(30).plot.bar(rot = 90)

potholes.value_counts().tail(10)
