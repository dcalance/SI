## Laboratory Work 2 SQL Injection:

# Tools used
1. Sqlmap

# Steps
1. Choose a vulnerable site. My choice was https://www.bible-history.com/
2. Using sqlmap scan a vulnerable link. After scanning we should get what kind of server is used and what type of Database.

![alt text](https://github.com/dcalance/SI/blob/master/res/lab2_1.png)

3. We use the --dbs argument to get the list of databases.

![alt text](https://github.com/dcalance/SI/blob/master/res/lab2_2.png)

4. We select a database using arugment -D and database name. We also use the argument --tables to list the tables from that database.

![alt text](https://github.com/dcalance/SI/blob/master/res/lab2_3.png)

5. We select the table with argument -T and use argument --columns to list the columns from that table.

![alt text](https://github.com/dcalance/SI/blob/master/res/lab2_4.png)

6. We use the argument -C to select columns we want and --dump to show all the entries in that table.

![alt text](https://github.com/dcalance/SI/blob/master/res/lab2_5.png)
