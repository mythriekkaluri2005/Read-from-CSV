# Read-from-CSV

## AIM:
To read from CSV file
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output.
## PROGRAM:
```
'''
Developed by: Ekkaluri Mythri
Ref.no:23003922
'''
import pandas as pd
f=pd.read_csv("/content/nba (2).csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:

![Screenshot 2023-12-27 171849](https://github.com/mythriekkaluri2005/Read-from-CSV/assets/150231422/ade15dcd-eba1-470f-a826-62cac7250467)



## RESULT:
Thus a python program is written to read the contents of a CSV file.
