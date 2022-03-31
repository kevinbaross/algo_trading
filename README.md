# Algorithmic Trading

This project utilizes machine learning methods to predict and backtest different trading algorithms.

---

## Technologies

This project leverages Jupyter notebook and Pandas.

---

## Installation Guide

Before running the application, please install the following libraries and dependencies

```python

import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
from sklearn.ensemble import AdaBoostClassifier

```

Then, clone the repository onto your local computer.

---

## Report and Findings


![model_summary](Resources/model_summary.png)


![original_plot](Resources/original_plot.png)

![original_report](Resources/original_report.png)


![ada_plot](Resources/ada_plot.png)

![ada_report](Resources/ada_report.png)



![test1_plot_train_shift_6_months](Resources/test1_plot_train_shift_6_months.png)

![test1_report_train_shift_6_months](Resources/test1_report_train_shift_6_months.png)

![test2_plot_change_SMA_10_200](Resources/test2_plot_change_SMA_10_200.png)

![test2_report_change_SMA_10_200](Resources/test2_report_change_SMA_10_200.png)

![test3_plot_change_SMA_5_50](Resources/test3_plot_change_SMA_5_50.png)

![test3_report_change_SMA_5_50](Resources/test3_report_change_SMA_5_50.png)

![test4_plot_train_shift_1_month](Resources/test4_plot_train_shift_1_month.png)

![test4_report_train_shift_1_month](Resources/test4_report_train_shift_1_month.png)


---

## Contributors

Initial code is provided by: UC Berkeley Fintech Bootcamp

Code is modified by: Kevin BaRoss [[LinkedIn](https://www.linkedin.com/in/kevin-baross/)]


---

## License
MIT
