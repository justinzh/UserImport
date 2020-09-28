# UserImport
importing user login info from .cvs to oracle DB with Talend script

this ETL process read user login records, cleans them and updats to oracle table

deployement:
the script runs on Talend TAC, and updating the same table in 4 DBs in production environment 

tigger:
the script is triggered by resource file change time tag change

table update:
table is truncated and loaded with new records
