# Build the project follow below steps
	1. Install mysql database
	2. Download the project zip folder and extract in your local machine
	3. Create a user account as "acdc" and password as "acdc"
	4. Navigate upto project location (..\registration-login-spring-xml-maven-jsp-mysql\src\main\resources)
	5. Look for db.sql file and exceute all the DB statements in the MySql
	6. Grant all permissions to the above created "accounts" on the user account acdc
	7. Navigate to upto ..\registration-login-spring-xml-maven-jsp-mysql
	8. Execute command "mvn clean install" on the command prompt
	9. After completion of the building of the project "target" folder will be genrated and copy the "account-1.0-SNAPSHOT.war" into the tomcat webapps folder
	10. Navigate to the tomcat bin folder and run the command "catalina.bat run" wait till tomcat server get's started
	11. Open the browser and access the application in the url bar as (http://localhost:8080/account-1.0-SNAPSHOT/login)
	
