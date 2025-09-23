# README — Line-by-line explanation of the notebook (2 Problems)

This README explains the code in the uploaded notebook `Asessment 2 (1).ipynb` grouped into **2 Problems**.
Each Problem contains the code (numbered) followed by line-by-line explanations.

## Problem 1

```python
001: #import numpy 
002: import numpy as np
003: 
004: #Generate random numbers 5 by 5
005: x = np.random.random((5,5))
006: 
007: #Making use of the mean function to calculate the mean of the random numbers 
008: mean = x.mean()
009: 
010: #calculating the standard Deviation
011: standard = x.std()
012: 
013: #Performing the formula by each of the random number
014: Normalize_X = (x - mean) / standard
015: 
016: #Print the results
017: print(Normalize_X)
018: 
019: np.save("X_Normalize.npy",Normalize_X)
020: 
021: #import the Numpy
022: import numpy as np
023: 
024: #Make an 1-100 numbers and power it by 2
025: arr1 = np.linspace(1,100,100,dtype = int) **2
026: #re-shape the numbers into 10 by 10 array
027: Nd = arr1.reshape(10,10)
028: 
029: #print the re-shaped numbers
030: print(Nd)
031: #initialize the list
032: div_by_3 = []
033: 
034: #make a loop to test each number
035: for i in arr1:
036: #check each number if divisible by 3 and if it is divisible it is going to the list of the initialized list
037:     if i % 3 ==0:
038:         div_by_3.append(i)
039: 
040: #saving the file 
041: np.save("div_by_3.npy",div_by_3)
042: #loading the file
043: np.load("div_by_3.npy")
044:     
```

**Line-by-line explanation:**

- Line 001: `#import numpy `  
  → Comment: import numpy
- Line 002: `import numpy as np`  
  → Executes the shown statement or operation.
- Line 003: *(blank line)*
- Line 004: `#Generate random numbers 5 by 5`  
  → Comment: Generate random numbers 5 by 5
- Line 005: `x = np.random.random((5,5))`  
  → Assigns the expression on the right to the variable `x`.
- Line 006: *(blank line)*
- Line 007: `#Making use of the mean function to calculate the mean of the random numbers `  
  → Comment: Making use of the mean function to calculate the mean of the random numbers
- Line 008: `mean = x.mean()`  
  → Assigns the expression on the right to the variable `mean`.
- Line 009: *(blank line)*
- Line 010: `#calculating the standard Deviation`  
  → Comment: calculating the standard Deviation
- Line 011: `standard = x.std()`  
  → Assigns the expression on the right to the variable `standard`.
- Line 012: *(blank line)*
- Line 013: `#Performing the formula by each of the random number`  
  → Comment: Performing the formula by each of the random number
- Line 014: `Normalize_X = (x - mean) / standard`  
  → Assigns the expression on the right to the variable `Normalize_X`.
- Line 015: *(blank line)*
- Line 016: `#Print the results`  
  → Comment: Print the results
- Line 017: `print(Normalize_X)`  
  → Prints the provided value to the output.
- Line 018: *(blank line)*
- Line 019: `np.save("X_Normalize.npy",Normalize_X)`  
  → Executes the shown statement or operation.
- Line 020: *(blank line)*
- Line 021: `#import the Numpy`  
  → Comment: import the Numpy
- Line 022: `import numpy as np`  
  → Executes the shown statement or operation.
- Line 023: *(blank line)*
- Line 024: `#Make an 1-100 numbers and power it by 2`  
  → Comment: Make an 1-100 numbers and power it by 2
- Line 025: `arr1 = np.linspace(1,100,100,dtype = int) **2`  
  → Assigns the expression on the right to the variable `arr1`.
- Line 026: `#re-shape the numbers into 10 by 10 array`  
  → Comment: re-shape the numbers into 10 by 10 array
- Line 027: `Nd = arr1.reshape(10,10)`  
  → Assigns the expression on the right to the variable `Nd`.
- Line 028: *(blank line)*
- Line 029: `#print the re-shaped numbers`  
  → Comment: print the re-shaped numbers
- Line 030: `print(Nd)`  
  → Prints the provided value to the output.
- Line 031: `#initialize the list`  
  → Comment: initialize the list
- Line 032: `div_by_3 = []`  
  → Assigns the expression on the right to the variable `div_by_3`.
- Line 033: *(blank line)*
- Line 034: `#make a loop to test each number`  
  → Comment: make a loop to test each number
- Line 035: `for i in arr1:`  
  → Starts a for-loop to iterate over items.
- Line 036: `#check each number if divisible by 3 and if it is divisible it is going to the list of the initialized list`  
  → Comment: check each number if divisible by 3 and if it is divisible it is going to the list of the initialized list
- Line 037: `    if i % 3 ==0:`  
  → Assigns the expression on the right to the variable `if i % 3`.
- Line 038: `        div_by_3.append(i)`  
  → Executes the shown statement or operation.
- Line 039: *(blank line)*
- Line 040: `#saving the file `  
  → Comment: saving the file
- Line 041: `np.save("div_by_3.npy",div_by_3)`  
  → Executes the shown statement or operation.
- Line 042: `#loading the file`  
  → Comment: loading the file
- Line 043: `np.load("div_by_3.npy")`  
  → Executes the shown statement or operation.
- Line 044: *(blank line)*

---

## Problem 2

```python
```

**Line-by-line explanation:**


---
