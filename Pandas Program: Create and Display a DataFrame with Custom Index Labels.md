# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd

# Create data
data = {
    "Name": ["John", "Alice", "Bob"],
    "Age": [25, 30, 22],
    "City": ["Chennai", "Delhi", "Mumbai"]
}

# Custom index labels
index_labels = ["A", "B", "C"]

# Create DataFrame
df = pd.DataFrame(data, index=index_labels)

# Display DataFrame
print(df)
```

## Output
```
    Name   Age     City
A   John    25   Chennai
B  Alice    30     Delhi
C    Bob    22    Mumbai
```
## Result
the code is verified.
