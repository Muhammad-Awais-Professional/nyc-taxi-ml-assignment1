[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Muhammad-Awais-Professional/nyc-taxi-ml-assignment1/blob/main/i222390_ML_A1.ipynb)

**Dataset Download:**

Since the dataset is too large to upload directly to GitHub, it is automatically downloaded using the following code in the notebook:

```python
url = "https://data.cityofnewyork.us/api/views/2yzn-sicd/rows.csv?accessType=DOWNLOAD"
df = pd.read_csv(url, nrows=2000000)
