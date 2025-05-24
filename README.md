# Read-from-CSV

## AIM:
To write a program to read a csv file.

## ALGORITHM:
### Step 1:
Import pandas module as pd
### Step 2:
Read a csv file
### Step 3:
Print the first five rows and last five rows
### Step 4:
Print the length of the rows and columns
### Step 5:
End the program
## PROGRAM:
```
#Write a program to read a csv file
#Developed by : Daksha Subbaian
#Reference no : 212223230036

from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
df=pd.read_csv('/content/drive/My Drive/cars.csv')
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/42fba6b1-0f0d-4a94-9ca4-941b191d659f)
![output](/excel.png)

## RESULT:
Thus the program is written to read a csv file.


