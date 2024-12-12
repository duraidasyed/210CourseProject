Requirements

To run the code successfully, ensure the following tools and libraries are installed:

Software

Python 3.8 or higher

Jupyter Lab

Python Libraries

pandas

numpy

matplotlib

seaborn

scikit-learn

psycopg2

Install the libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn psycopg2

Note: If the cell relating to connecting to the database presents an error, ensure you have psycopg2 installed in the working kernel, and try to run the cell again after restarting the kernel.


Input File

Filename: all_stocks_5yr.csv

Description: Five years of historical stock prices for all companies in the S&P 500 index.

Columns:

Date: The trading date.

Open, High, Low, Close: Prices for the stock.

Volume: Number of shares traded.

Name: Stock ticker name.


Troubleshooting

File Upload Error: Ensure the file size does not exceed the platform’s upload limits.
If there is an issue with the submission, find the dataset online at https://www.kaggle.com/datasets/camnugent/sandp500/data

Memory Issues: Reduce the dataset size by sampling rows.

Library Errors: Ensure all required libraries are installed and up to date.



