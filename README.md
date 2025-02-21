# Python-Assignment-1


Pre requistes:
Jupyter Notebook
SQlite DB

I have created the python code in jupyter notebook and used SQLite DB for database. Ensure that you have installed those in your system or else
you can use any other python editor and mentioned code only works for SQLite DB(conn = sqlite3.connect(db_name))


Run the jupyter notebook file cell by cell till TASK 4.
Check the result in thr SQLite DB (Make sure you open the database from the location)
Run TASK 4 to see the results of python functions to validate data
Run sql queries mentioned after python functions in SQLlite DB to verify the results


Assumptions made:
Data in excel A and excel b are identical, so made an assumption that same order ids can exist in different excels, else while removing duplicates one excel would completely get removed.

First the business rules transformations are applied on both excels separately and then both regions are combined into a single table as per business rule 1. Duplicate orderIds are removed from each excel separately.
