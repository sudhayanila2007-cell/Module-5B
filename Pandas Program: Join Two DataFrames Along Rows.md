# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd

# First DataFrame
df1 = pd.DataFrame({
    "Name": ["John", "Alice"],
    "Age": [25, 30]
})

# Second DataFrame
df2 = pd.DataFrame({
    "Name": ["Bob", "David"],
    "Age": [22, 28]
})

# Join along rows
result = pd.concat([df1, df2])

print(result)
```

## Output
```
    Name  Age
0   John   25
1  Alice   30
0    Bob   22
1  David   28
```

## Result
the code is verified.
