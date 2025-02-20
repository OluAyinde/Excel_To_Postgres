This script was created to import data from excel sheets in a workbook into multiple tables that have been created in a postgresql database.


- The part that states `postgres` should be `your database username`. (it mostly is postgres as most people don't change that).
- The part that states `password.` should be `your database password`.
- The default PostgreSQL port is `5432`.
- The part that states `database_name` should be the `name of your database` with the empty tables.
- Input `your file path` where it states `your_file.xlsx`. Also, please make sure to save your Excel workbook as an Excel file and not csv.

The `if_exists='replace'` argument in `to_sql` will replace the table if it already exists. You can change it to `‘append’` if you want to add data to an existing table.

You can also find a walkthrough [here](https://medium.com/@aoluf/importing-tables-from-multiple-excel-spreadsheets-to-postgresql-a0947c43c357)
