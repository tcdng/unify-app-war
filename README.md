## Unify Application - Web Application Resource (WAR)
This starter provides a project template for building applications using Unify Framework that will be deployed on any standard Java web server. Suitable web servers must run on Java 6 at minimum and must support at least Servlet 3.0.

Uses in-memory HSQLDB as application database and utilizes port 8081 for command interface by default. You can change database and port settings in ...\WEB-INF\conf\unify.xml.

## Build the Project

```
mvn clean package
```
 
### Quick Run
* Download an already assembled deployable package here.
* Deploy downloaded WAR file into suitable web server.
* Open a browser and enter http://localhost:<Port Number>/unify into the address bar.
