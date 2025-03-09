This script was created to import data from excel sheets in a workbook into multiple tables that have been created in a postgresql database.

When calling the `function`:
- The part that states `postgres` in the function should be `your database username`. (it mostly is `postgres` as most people don't change that).
- The part that states `password.` should be `your database password`.
- The default PostgreSQL port is `5432` except this is different in your case.
- The part that states `database_name` should be the `name of your database` with the created empty tables.
- Input `your file path` where it states `your_file.xlsx`. Also, please make sure to save your Excel workbook as an `Excel file` and not csv.
- The `if_exists='replace'` is a default parameter in the function and will replace the table if it already exists. You can change it to `'append'` when calling the function if you want to add data to an existing table, `i.e. if_exists='append'`.

You can also find a walkthrough [here](https://medium.com/@aoluf/importing-tables-from-multiple-excel-spreadsheets-to-postgresql-a0947c43c357)