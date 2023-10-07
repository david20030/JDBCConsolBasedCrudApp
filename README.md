# JDBCConsolBasedCrudApp
    This is a Consol based Application for JDBC CRUD operation(MYSQL Database)
	# Requirements
	1.MYSQL Database having database name - "student",and table name - "studentinfo" having column names
	  i. sid(int Auto-increment) ii. sname (varchar)  iii. sage (int) iv. saddress (varchar)
	2.Add your databse username and password in the line  
	connection = DriverManager.getConnection("jdbc:mysql://localhost:3306/student","username","password");
	and perform CRUD operation using this program 
	3. download mysql-connector-jar and
	4.set classpath
            i.In windows open cmd and run command (set classpath=;.;"enter the path of the .jar")
           ii. Inlinux (java -cp .:pathOf.jarFile  Main) or (export CLASSPATH=/path/to/jar1.jar:. )
	       

