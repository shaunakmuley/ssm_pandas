# ssm_pandas

start with import pandas as pd

2 core objects in panas
1. dataframe:
  pd.DataFrame({'ssm':[1,2,3],'skm':[5,6,7]})
  it is like dictionary but not dictionary
  here ssm and skm is the column name and 123 and 567 are the rows in in this way we create table in pandas and we can also give row name for example
  pd.DataFrame({'ssm':[1,2,3],'skm':[5,6,7]},index=['r1','r2','r3'])

2.series:
  pd.Series([1,2,3,4,5])
  This will create table with 2 columns where 1,2,3,4,5 are value in 2nd col and 1st col values will be 0,1,2,3,4 we can also assign values to rows like above in       dataframe like 
  pd.Series([30, 35, 40], index=['2015 Sales', '2016 Sales', '2017 Sales'], name='Product A') 



how to read file:
file = pd.read_csv("file path")


different commands for playing:
if confused check what they do with the help of google or ai tools

file.shape
file.head
file.tail
file.info
file.describe
file.isnull
file.sum
file.isnull().sum
file.duplicated
file.index
file.dtypes
df.mean
df.median
df.mode

