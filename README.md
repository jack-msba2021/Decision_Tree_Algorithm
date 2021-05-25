# Decision Tree Algorithm
![Given a data of attributes together with its classes, a decision tree produces a sequence of rules that can be used to classify the data.
](https://developers.bloomreach.com/binaries/original/content/gallery/developer/blog/decision-tree.jpg)

Given a data of attributes together with its classes, a decision tree produces a sequence of rules that can be used to classify the data.
## Project Description
This project practices using the DecisionTreeClassifier algorithm from scikit learn to predict the income class of an individual. The dataset for this project comes from the US Census Bureau and represents salaries of people along with seven demographic variables. The target class is binary (>50K or <=50K) and our variables have been discretized into categories.

To find the best tree, hyperparameters such as maximum depth, maximum features, and minimum sample leaf were varied, with their accuracies being plotted in subsequent order and plotted via visualizations. 

## Steps

 1. Data Cleaning and Exploration
 2. Building Decision Tree Classifier
 3. Evaluating Performance
 4. Finalizing Best Tree

## Requirements
The following can be used to run Python code:
 - [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
 - [Jupiter Notebook](https://jupyter.org)

### Installation
The following packages are required to run this project:
```python
import math
import numpy as np
import pandas as pd
from datetime import datetime
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
plt.style.use('seaborn-whitegrid')
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import classification_report
from sklearn.metrics import confusion_matrix
```
### Data
Make sure to download the data file and upload it to the Google Colab project files.

## Project Files
Access the Decision Tree project [here](https://drive.google.com/file/d/1nm-2xGiR_4Lxb8OBK1xLnQ1mcJlFeS3V/view?usp=sharing).

View the data exploration steps [here](https://drive.google.com/file/d/1fvUH7fAY5GYPpEydGC_kmbO3QISBGxws/view?usp=sharing).

## Authors
[Jack Taylor](https://www.linkedin.com/in/jack-taylor-su/)

## Credits and Acknowledgments
Thank you Professor [Arin Brahma](https://github.com/ArinB) of Loyola Marymount University for providing the file template.

## License
[MIT](https://choosealicense.com/licenses/mit/)

