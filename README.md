# java-_database-_connection
Five steps for database connection
1.Register the driver class(use forName() method)
2.Create the Connection object(getConnection() method of driver Manager class is used to estavlish the connection with the database)
3.Create the statement Object(the createStatement() method of connection interface is used to create statement.The object of statement is responsible to execute queries with the database)
4.Execute the Query(The executeQuery() method of statement interface is used to execute queries to the databse this method returns the object of resultset that can be used to get all the records of the table)
5.Close the connection object(by closing connection object statement .Resultset will be close automatically.The close() method of connection interface is used to close the connection)
Requirements: Aquadata,postgresql,myeclipse10

Before doing this using aquadata register server,create databse and connect server.(record database name,portnumber and password.)

