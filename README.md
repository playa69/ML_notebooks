# ML_notebooks

CSV in "../data/%name%.csv" or seaborn

Also more ds here https://www.kaggle.com/datasets:

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
