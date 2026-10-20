# datasets-for-ml-projects

A small collection of datasets used in my machine learning and data analysis projects.

## Contents

| File | Format | Description |
|------|--------|-------------|
| `LungCap.xls` | Excel | Lung capacity data, a common dataset for regression and statistics practice |
| `train_data.csv` | CSV | Table of medical image file names (`file_name`) with a binary label (`target`), used for image classification experiments |

## Usage

```python
import pandas as pd

lung = pd.read_excel("LungCap.xls")
train = pd.read_csv("train_data.csv")
```

Reading `.xls` files needs the `xlrd` package (`pip install xlrd`).

## Note

`train_data.csv` lists image file names only. The images themselves are not included in this repo.
