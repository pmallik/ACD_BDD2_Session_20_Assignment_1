# ACD_BDD2_Session_20_Assignment_1
Sqoop Assignment 20

Session 20 Assignment 1

1. Perform UPSERT in Sqoop export. 
Read a file from HDFS and based on the id field, perform UPSERT in MySQL table. 
In UPSERT, if the field exists, then it is updated else it is inserted. 

1. Created emp table in Mysql database.
2. created text file emp.txt
1,puja
2,rekha
3,sonali
4,raju
5,ramesh

3. Put the emp.txt file in HDFS

4. Run the sqoop export command to save data in the emp table in mysql database.

5. Modify the emp.txt file as below and stored the file again HDFS using put

1,puja
2,rekha
3,sonalu
4,raju
5,radha
6,ramesh

6. Run the sqoop export command and used update mode : allowinsert to perform the upsert.
