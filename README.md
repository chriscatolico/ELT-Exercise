# ETL-Exercise

Healthcare company stock data was pulled from Nasdaq and uploaded into a database. Additionally, the number of company sponsored clinical
trials were uploaded into the database. These data sets were chosen to monitor the number of clinical trials of publicly traded healthcare
companies.

*Extract*

Nasdaq list of healthcare companies along with stock information (csv) from:
https://www.nasdaq.com/screening/companies-by-industry.aspx?industry=Health+Care

Clinical trials list and count by sponser/company (html) from:
https://clinicaltrials.gov/ct2/search/browse?brwse=spns_alpha_all

*Transform*

Created data frames from extracts and cleaned columns, titles, and values.

*Load*

The final database where the dataframes were uploaded as tables was sqlite. This database type was chosen because
it is relational and sqlalchemy works easily with pandas.
