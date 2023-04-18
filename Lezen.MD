# p2-k2
p2-k2 examen



Description
Company name 
Verified signer 
Version 
Command line 
Virus total 




Datalek uit database 

Achterhalen laatste query en database log uitlezen

Query uitdraaien van mensen in DB achternaam met A 

Wanneer hoeveel records verdwenen


SHOW FULL PROCESSLIST
ORDER BY Time DESC
LIMIT 1;


In MySQL, the logs are typically located in the MySQL data directory on your server. The exact location of the logs can vary depending on your server configuration, but the most common paths are:

Linux: /var/log/mysql/
Windows: C:\ProgramData\MySQL\MySQL Server X.X\data
To access the logs, you can use a text editor or command line tools such as "less" or "tail" to open the log files and view their contents.

The main log files in MySQL are:

Error log: This file contains information about errors and warnings that occur during server startup, shutdown, and while the server is running.
General query log: This file contains a record of all the SQL statements that are executed on the server.
Slow query log: This file contains information about queries that take longer than a certain threshold to execute.
To enable or disable logging in MySQL, you can modify the server configuration file (my.cnf or my.ini). The settings for each type of log are:

Error log: "log_error"
General query log: "general_log" and "general_log_file"
Slow query log: "slow_query_log" and "slow_query_log_file"
Note that enabling logging can have a performance impact on your server, so it's recommended to only enable it when necessary. Also, be sure to secure the log files to prevent unauthorized access to sensitive information.

