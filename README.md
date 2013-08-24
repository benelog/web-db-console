web-db-console
==============
A JDBC client with web interface by Maven-exec-plugin and H2 console.

## Usage
1. Download.

		git clone https://github.com/benelog/web-db-console.git

2. Execute.

		cd web-db-console
		mvn exec:java

3. Your web browser will show the UI of H2 Console.

	![Login](http://file.benelog.net/web-db-console/console1.png)
	![SQL Editor](http://file.benelog.net/web-db-console/console2.png)

The data sources may be any DBMS supporting JDBC. You can add JDBC drivers in pom.xml. The following example is for MariaDB.

		<dependency>
			<groupId>org.jumpmind.symmetric.jdbc</groupId>
			<artifactId>mariadb-java-client</artifactId>
			<version>1.1.1</version>
		</dependency>
