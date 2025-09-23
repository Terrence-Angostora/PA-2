# PRACTICE ASSESSMENT #2
### Documentation

### PROBLEM #1 Normalization Problem
######
###### ![image](https://github.com/user-attachments/assets/8a1ac54e-ed9c-4deb-ad8c-959023014072)

#### Insights: 
###### The provided Python code effectively normalizes a random 5x5 matrix, a common preprocessing technique in data analysis. By importing the NumPy library, the code gains access to essential functions for numerical operations and array manipulation. The generation of a random matrix using np.random.random() establishes a dataset for testing and demonstration purposes.

##### The calculation of mean and standard deviation using mean() and std() is a crucial step, as these values are used in the normalization process. The formula (x - mean) / std effectively centers the values around 0 and scales them to have a standard deviation of 1, ensuring that features contribute equally to subsequent calculations or models.

##### The printing of the normalized matrix provides a visual representation of the results, allowing for inspection and verification. Additionally, saving the normalized matrix to a file using np.save() enables its future use or analysis. This code snippet serves as a valuable example of how normalization can be implemented in Python using the NumPy library.


### Sample Code for the Problem: 
### ![image](https://github.com/user-attachments/assets/b317744e-1be3-4ce4-9fcf-f2589d88823e)


### Output for the Code: 
### ![image](https://github.com/user-attachments/assets/9e8de645-3d33-4950-b74f-10e0efeef85d)

### Problem #2 Divisible by 3 Problem

##### 2. 
##### ![image](https://github.com/user-attachments/assets/54c10dce-dce5-46b6-b47f-686f4b7cf46e)

##### Insights
##### The provided Python code demonstrates the process of identifying elements divisible by 3 within a 10x10 NumPy array containing the squares of the first 100 positive integers. By importing the NumPy library, the code gains access to essential functions for array manipulation and mathematical operations. The creation of an array of squares using np.linspace and subsequent reshaping into a 10x10 matrix establishes the dataset for analysis.

##### The code iterates through each element of the array, checking for divisibility by 3 using the modulo operator (%). Elements divisible by 3 are appended to a list named div_by_3. The resulting list is then saved to a .npy file named "div_by_3.npy" using np.save(). This file can be loaded back using np.load() for future reference or analysis.

### Sample Code for the problem:
### ![image](https://github.com/user-attachments/assets/90423ed6-e1ed-4cf7-a413-d6492c3d6072)

### Output: 
### ![image](https://github.com/user-attachments/assets/39c64e9c-1bf6-451f-9796-0d52352fc2cb)
