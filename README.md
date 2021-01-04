# python-pandas

**ABSTRACT**    
 This is a study note of Sensor Cloud in Kookmin University about data processing using pandas. 


## 1. What is Pandas?   

<img src="https://github.com/SeiwonPark/python-pandas/blob/main/images/logo.jpeg" width="500">   


### 1.1 The origin of the term, Pandas
'Pandas' was originated from the term 'panel data', an econometrics term for data sets that include observations over multiple time periods for the same individuals. 
Time-series and cross-sectional data can be thought of as special cases of panel data that are in one dimension only. 
Pandas is a high-level data manipulation tool developed by _Wes McKinney_. 
It is built on the Numpy package and so Numpy is required to operate Pandas. And its key data structure is called the DataFrame. 
DataFrame allows you to store and manipulate tabular data in rows of observations and columns of variables.

<br/>   

## 2. Features   
### 2.1 Series   

> Series is a one-dimensional labeled array capable of holding **any data type** (integers, strings, floating point numbers, Python objects, etc.). The axis labels are collectively referred to as the index.   


### 2.2 Dataframes   

> DataFrame is a 2-dimensional labeled data structure with columns of **potentially different types**. You can think of it like a spreadsheet or SQL table, or a dict of Series objects. It is generally the most commonly used pandas object. Like Series, DataFrame accepts many different kinds of input:   

* Dict of 1D ndarrays, lists, dicts, or Series
* 2-D numpy.ndarray
* Structured or record ndarray
* A Series
* Another DataFrame     


<br/>   

## 3. How to Use

* Read / Write files(`.csv`, `.txt`, `.xml`)
   [https://github.com/SeiwonPark/python-pandas/blob/main/read_write_files.ipynb](https://github.com/SeiwonPark/python-pandas/blob/main/read_write_files.ipynb)
* Series and Dataframe
   [https://github.com/SeiwonPark/python-pandas/blob/main/series_n_dataframe.ipynb](https://github.com/SeiwonPark/python-pandas/blob/main/series_n_dataframe.ipynb)
* Analyze COVID 19 data(test)
   [https://github.com/SeiwonPark/python-pandas/blob/main/analyze_covid19_data.ipynb](https://github.com/SeiwonPark/python-pandas/blob/main/analyze_covid19_data.ipynb)
* Combine dataframes
   [https://github.com/SeiwonPark/python-pandas/blob/main/combine_dataframes.ipynb](https://github.com/SeiwonPark/python-pandas/blob/main/combine_dataframes.ipynb)

<br/>   


## 4. Extra   

### 4.1 R vs Python
Both R and Python are open source programming language. R is mainly used for statistical analysis while Python provides a more general approach to data science. 
But as Python makes replicability and accessibility easier than R, Python is recommended when you're doing data processing. 


#### Key Difference 
* The primary objective of R is Data Analysis and Statistics whereas the primary objective of Python is Deployment and Production   
* R users mainly consists of Scholars and R&D professionals while Python users are mostly Programmers and Developers   
* R provides flexibility to use available libraries whereas Python provides flexibility to construct new models from scratch   
* R is integrated to run locally while Python is well-integrated with apps   


### 4.2 Numpy vs Pandas   
To begin with, Numpy is a library for scientific computing. Numpy array is a powerful N-dimensional array object which is in the form of rows and columns. Data types in Numpy should be the same but those in Pandas can have various types as mentioned above.


#### Key Difference 
* The Pandas module mainly works with the tabular data, whereas the NumPy module works with the numerical data
* Pandas provides 2-d array(table data structure) and it can hold various types of data but Numpy provides n-d array and it can hold a single data type
* NumPy consumes less memory than Pandas
* NumPy has a better performance for 50,000 rows or less whereas	Pandas has a better performance for 500,000 rows or more


### 4.3 Pandas vs Matplotlib   
Basically the purpose of using them is quite different. Pandas is more about data analysis but Matplotlib is more about plotting and visualizing. But in some ways they provides similar functions. When plotting they both produce a matplotlib object. However they are different. 
In case they make bar plots, Pandas plots are categorized so each bars are continuous, but Matplotlib plots have numerical indexes so it could be discontinuous.   


<br/>   


## Reference   
* [https://en.wikipedia.org/wiki/Pandas_(software)](https://en.wikipedia.org/wiki/Pandas_(software))
* [https://pandas.pydata.org](https://pandas.pydata.org)
* [https://www.kaggle.com/learn/pandas](https://www.kaggle.com/learn/pandas)
* [https://www.tutorialspoint.com/python_pandas/index.htm](https://www.tutorialspoint.com/python_pandas/index.htm)
* [https://www.javatpoint.com/python-pandas](https://www.javatpoint.com/python-pandas)
* [http://jonathansoma.com/lede/algorithms-2017/classes/fuzziness-matplotlib/understand-df-plot-in-pandas/](http://jonathansoma.com/lede/algorithms-2017/classes/fuzziness-matplotlib/understand-df-plot-in-pandas/)
