# TEN Internship – Day 1: Conda & JupyterLab Setup

## Overview
This repository contains my Day 1 internship work, focusing on setting up a Python environment using Conda and JupyterLab and practising basic data analysis with NumPy and Pandas.

## Environment Setup
- **Python:** 3.11.18
- **Conda Environment:** `ten-datascience`
- **IDE:** JupyterLab

## Libraries Installed
- NumPy
- Pandas
- Matplotlib
- IPython Kernel

## Tasks Completed
1. Installed Miniconda.
2. Created a separate Conda environment.
3. Installed and launched JupyterLab.
4. Practised NumPy array operations:
   - Sum
   - Average
   - Maximum
   - Minimum
5. Created a Pandas DataFrame.
6. Practised filtering and sorting student records.
7. Verified the installed Python libraries.

## Sample Operations

### NumPy
```python
import numpy as np

numbers = np.array([10, 20, 30, 40, 50])

print(np.sum(numbers))
print(np.mean(numbers))
```

### Pandas
```python
import pandas as pd

data = {
    "Name": ["Aswini", "Charu", "Aishwarya"],
    "Marks": [85, 90, 95]
}

df = pd.DataFrame(data)
display(df)
```

## How to Run
1. Clone this repository.
2. Activate the Conda environment.
3. Launch JupyterLab.
4. Open `TEN_Day1_Setup.ipynb`.
5. Run the notebook cells.

## Author
**Aswini R I**

AI Internship – The Entrepreneurship Network (TEN)

Employee ID: TEN/AI/17271616
