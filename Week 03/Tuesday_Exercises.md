Here are **10 practical exercises** on NumPy and Pandas, structured into separate blocks clearly for your class:

---

## 📗 **NumPy Exercises**

---

### 📝 **Exercise 1: Basic NumPy Array**

* Create a NumPy array containing numbers from **1 to 10**.
* Print the array and its data type.

---

### 📝 **Exercise 2: Array Operations**

* Create a NumPy array of numbers from **10 to 20**.
* Calculate and print the sum, average, maximum, and minimum values.

---

### 📝 **Exercise 3: NumPy Array Slicing**

* Create a NumPy array with numbers **from 1 to 20**.
* Print all even numbers in the array.

---

### 📝 **Exercise 4: NumPy Array Reshape**

* Create a NumPy array containing numbers from **1 to 12**.
* Reshape this array into a **3x4 matrix** and print it.

---

### 📝 **Exercise 5: NumPy Random Numbers**

* Create a NumPy array of **5 random integers between 1 and 100**.
* Print this array and also print its highest and lowest numbers.

---

## 📙 **Pandas Exercises**

---

### 📝 **Exercise 6: Create Basic DataFrame**

* Create a Pandas DataFrame with these columns:

  * `Name`: \['Anna', 'Bob', 'Charlie']
  * `Age`: \[25, 30, 35]
  * `Country`: \['UK', 'USA', 'Canada']
* Print the DataFrame.

---

### 📝 **Exercise 7: Basic DataFrame Info**

* Using the DataFrame from Exercise 6:

  * Print basic information about the DataFrame using `.info()`.
  * Print the first 2 rows using `.head()`.

---

### 📝 **Exercise 8: Filter DataFrame**

* Create a DataFrame with columns `Product`, `Price`, and `Quantity`.
* Filter and print products with a price **greater than 50**.

---

### 📝 **Exercise 9: CSV Reading & Writing**

* Create a DataFrame with 3 students (`Name` and `Score`).
* Write this DataFrame to a CSV file named `"students.csv"`.
* Read the CSV file again into a new DataFrame and print it.

---

### 📝 **Exercise 10: Data Cleaning**

* Create a DataFrame with some missing values:

```python
data = {
  'Name': ['Anna', None, 'Charlie'],
  'Age': [25, None, 35],
  'Country': ['UK', 'USA', None]
}
```

* Replace all missing values with `"Unknown"` or average age for numeric values.
* Print the cleaned DataFrame.