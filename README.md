# Metro-Interstate-Traffic-Volume-Analysis
from google.colab import files
uploaded = files.upload()
import pandas as pd

df = pd.read_csv("Metro_Interstate_Traffic_Volume.csv")
df.head()
