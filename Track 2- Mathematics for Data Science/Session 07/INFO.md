`Date`: 9 Oct 22 No. 07

`Subject`: Pandas

# Notes

- Pyspark: Data processing and modeling with machine learning.
- Dask: Parallel processing and loading data into virtual memory.
- `descripe()` function only works on numerical data.
- `value_counts()` functions works on string data.
- To read data from Website 
  ```
  import io
  import requests
  url = "  data_url  "
  s = requests.get(url).content
  data = pd.read_csv(io.StringIO(s.decode('utf-8')))
  data
  ```
  
- DataFrames can be created by using (csv, excel sheet, tubles list, dictionary or list of dictionaries)
# Tasks
