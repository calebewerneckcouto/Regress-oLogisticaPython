# Social Network Ads Dataset Analytics

## Overview
This repository contains a CSV dataset named `Social_Network_Ads.csv`, which includes demographic information and purchasing behavior of users on a social network. This dataset is utilized to analyze and predict user behavior concerning product purchases based on their age and estimated salary.

## Dataset Description
The `Social_Network_Ads.csv` file comprises the following columns:
- **Age**: The age of the user.
- **EstimatedSalary**: The estimated salary of the user.
- **Purchased**: A binary variable indicating whether the user purchased the product (1) or not (0).

### Sample Data
```
Age,EstimatedSalary,Purchased
19,19000,0
35,20000,0
26,43000,0
...
35,27000,0
33,28000,0
30,49000,0
```

## Repository Files Description
- `.gitignore`: Contains files and directories to be ignored in version control, including the Python virtual environment directory `venv/`.
- `README.md`: This file, providing an overview and instructions.
- `Social_Network_Ads.csv`: The main dataset used for analysis.

## Usage
To analyze this dataset, follow these steps:
1. Clone this repository to your local machine.
2. Ensure you have Python installed and optionally set up a virtual environment.
3. Install necessary Python libraries such as `pandas` for data manipulation and `matplotlib` or `seaborn` for data visualization. Use the following command to install libraries:
   ```
   pip install pandas matplotlib seaborn
   ```
4. Load the dataset using Pandas and perform your data analysis and visualization as required.

## Example Analysis
You can perform a simple data analysis to understand purchasing behavior by age and salary. Here is an example using Python:
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load data
df = pd.read_csv('Social_Network_Ads.csv')

# Display statistics
print(df.describe())

# Plotting distribution of age and salary by purchased
sns.pairplot(df, hue='Purchased')
plt.show()
```

## Contribute
Contributions to expand or enhance the dataset analysis are welcome. Please fork the repository and submit a pull request with your suggested changes.

## License
This dataset and accompanying analysis are provided for educational purposes and are not associated with any real individuals or events. Please use and share responsibly.
Escrevendo README no GitHub...
