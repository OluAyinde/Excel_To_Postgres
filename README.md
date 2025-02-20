This script was created to import data from excel sheets in a workbook into multiple tables that have been created in a postgresql database.

The `if_exists='replace'` argument in `to_sql` will replace the table if it already exists. You can change it to `‘append’` if you want to add data to an existing table.

You can also find a walkthrough [here](https://medium.com/@aoluf/importing-tables-from-multiple-excel-spreadsheets-to-postgresql-a0947c43c357)
