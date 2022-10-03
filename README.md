# Build the project follow below steps
	1. Install mysql database
	2. Create a user account as "acdc" and password as "acdc"
	3. Navigate upto project location (..\registration-login-spring-xml-maven-jsp-mysql\src\main\resources)
	4. Look for db.sql file and exceute all the DB statements in the MySql
	5. Grant all permissions to the above created "accounts" on the user account acdc
	6. Navigate to upto ..\registration-login-spring-xml-maven-jsp-mysql
	7. Execute command "mvn clean install" on the command prompt
	8. After completion of the building of the project "target" folder will be genrated and copy the "account-1.0-SNAPSHOT.war" into the tomcat webapps folder
	9. Navigate to the tomcat bin folder and run the command "catalina.bat run" wait till tomcat server get's started
	10. Open the browser and access the application in the url bar as (http://localhost:8080/account-1.0-SNAPSHOT/login)
	