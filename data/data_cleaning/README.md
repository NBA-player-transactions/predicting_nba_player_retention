# Data Cleaning

In this folder, we clean and organize the data that was collected in the data
collection folder. The end result is a single csv file `full_data.csv`
containing the full data set. It is located in the subfolder `merged_data`. Our
process to generate this data set is to first clean each category of data that
we collected. More specifically, for each category:

- Advanced stats
- Counting stats
- Salaries
- Transactions,

we create a subfolder cleaning the corresponding data. Each subfolder contains
the following:

- Jupyter notebook(s) cleaning the data
- One or more csv file(s) containing the cleaned data.

Next, in the subfolder `merged_data`, we merge this data. The merge
itself is done in a Jupyter notebook that generates the file `full_data.csv`.

We also have a subfolder named `helper_files` which contains some useful
auxiliary files to assist in the data cleaning process.
