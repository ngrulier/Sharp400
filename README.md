Sharp400
========

a C # library to access a system As400 from a program. NET

Developped with SharpDevelop 3.2

I want to develop 3 classes to communicate with an AS400 system from a .Net programm.



Setp 1 : Done
   - SQL 
      - Open a connection with the DB2 database
          - show a gui to type user ident if needed
      - Send a query select and read result in odbcdatareader
      - send a query non select
      - send an AS400 command throw an sql non select query
      - close the connection

Setp 2 : in progress
  - FTP
      - Open a FTP connection
          - show a gui to type user ident if needed
      - List file and member in a library
      - download a member
      - uplad a member

Step 3 : in progress
  - CMD 
  This class describes many common commands AS400
  Used with SQL.send an AS400 command
      
