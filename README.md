# ALFARO, Emmanuel John | 2ECE-A
# PA#3 - PYTHON DATA ANALYSIS (PANDAS)

## Objectives
- Identify codes and its functions in the Panda Library
- Appltand use Pandas functions in the problems

### Problem 1
```
import pandas as pd

```
- use to import the Pandas library which is use for data manipulation and analysis

<br>

```
cars = pd.read_csv('cars.csv')

```
- use to read a CSV file and in this task we are tasked to load the file 'cars.csv'

<br>

```
cars.head (5)

```
- this code use to show the first 5 rows of the DataFrame

<br>

```
cars.tail (5)

```
- this code shows the last 5 rows of the data set

### Problem 2

```
cars.iloc[:5, 1::2]

```

- This code displays the first five rows with odd numbered columns

<br>

```
cars[0:1]

```
- this code is use to  slice the dataframe. We are tasked to display the row that contains the Model "Mazda RX4"

  <br>

```

cars.loc[(cars['Model'] == 'Camaro Z28'), ['Model', 'cyl']]

```

- this code creates a filter that is true in the given condition. In this part we are tasked to display how many cylinder in the car model Camaro Z28

<br>

```
cars.loc[[1,28,18], ['Model', 'cyl', 'gear']]

```

- Code displays in given rows by the index numbers. In this problem we are tasked to display the cylinders and gear in the given car models
