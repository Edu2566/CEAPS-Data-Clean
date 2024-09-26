# Expense Data Processing

This Jupyter Notebook contains a series of data processing steps for analyzing expense data from the `despesa_ceaps_2022.csv` file. The data is processed using the Pandas library in Python.

## Description

The notebook performs the following tasks:

1. **Load Data**: Import the expense data from a CSV file with a specified delimiter, encoding, and decimal format.
2. **Display Data Information**: Show information about the loaded data, including the number of entries and column data types.
3. **Remove Empty Rows**: Drop all rows where the `DOCUMENTO` column is empty to ensure data integrity.
4. **Fill Missing Values**: Replace empty values in the `DETALHAMENTO` column with the text "Detalhamento não Especificado" to provide a default description.
5. **Standardize Text Case**: Convert all entries in the `FORNECEDOR` column to uppercase to maintain consistency in naming conventions.
6. **Final Display**: Show the updated information and the entire processed table.

## Requirements

- Python 3.12.2
- Pandas library

You can install the required library using pip:

```bash
pip install pandas
