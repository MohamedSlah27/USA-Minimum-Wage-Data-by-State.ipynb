# USA-Minimum-Wage-Data-by-State.ipynb

In this project, I utilized my skills in data manipulation, analysis, and visualization.The project involves in reading a CSV file, grouping the data by state and year, creating a new DataFrame to store the minimum wage values, and performing data analysis and visualization tasks such as descriptive statistics, correlation, and covariance calculations.the following steps demostrates how i utulized my skills:

Data Loading: I started by importing the necessary libraries, such as pandas and numpy, to work with data in Python. Then, it reads a CSV file containing minimum wage data into a pandas DataFrame.

Data Cleaning: I read a CSV file using the pd.read_csv() function from pandas. Initially, I then encountered an error because the file was not saved as UTF-8 encoding. To resolve this, I saved the data to a new CSV file with UTF-8 encoding.

Data Manipulation: The DataFrame is then used to perform various data manipulation tasks. Firstly, I grouped the data by the "State" column using the groupby() function. I created a group for the state of Alabama by year.It demonstrates grouping for the "Alabama" state by year by accessing the group using gb.get_group("Alabama") and setting the index to "Year".

Iterating over Groups: Next, I creates an empty DataFrame called "act_min_wage". It iterates over each group (state) in the original DataFrame and appends the "Department.Of.Labor.Cleaned.Low.Value.2020.Dollars" column to the "act_min_wage" DataFrame. This process is repeated for all states, resulting in a DataFrame where each column represents a state's minimum wage over the years.

Data Analysis:I then performs analysis on the "act_min_wage" DataFrame. It calculates descriptive statistics using the describe() method, providing statistical measures like count, mean, standard deviation, and quartiles for each state's minimum wage.

Correlation and Covariance: Lastly, I created the correlation and covariance matrices using the corr() and cov() methods, respectively, on the "act_min_wage" DataFrame. These matrices provide insights into the relationships and variations between different state minimum wages.





















