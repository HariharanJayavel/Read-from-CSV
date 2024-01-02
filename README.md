# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Using pd.read_csv() method read the CSV file.
### Step 3:
Using df.head() print the first 10 rows of the CSV file.
### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column

## PROGRAM:
### Python program to read contents from a csv file
### Developed by: HARIHARAN J
### Register Number: 212223240047
```

import pandas as pd
df = pd.read_csv('cars.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2023-12-31 154846](https://github.com/HariharanJayavel/Read-from-CSV/assets/144870546/15bd9e4a-344a-4bd1-99a2-a9cf334ddabd)

## RESULT:
Thus a python program is written to read the contents of a CSV file
