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
![image](https://github.com/HariharanJayavel/Read-from-CSV/assets/144870546/d0bcd4d0-83ff-4bec-95be-92665f975346)

## RESULT:
Thus a python program is written to read the contents of a CSV file
