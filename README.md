# How to Make a Web Application Using Spring Boot
This project illustrates how to develop a "Hello World" web application using Spring Boot, a server-side programming tool.
## Task-I
* Generate Maven project at [Spring Initializr](https://start.spring.io). 
* This Maven project tutorial uses *Java* JDK 17 and *Spring Boot* 2.5.5.
* In the **Project Metadata**, set name to "demo" and set all other parameters to default.
* Unzip the file in any directory on your computer. In this tutorial, the directory name is **demo**.
* Open *Command Prompt/Terminal/Console*.
* Navigate to the path you unzip the file and get into directory **demo**.
* Run the application using the command *mvn spring-boot:run*. 
## Task-II
Make following changes.
* Add dependencies in the *pom.xml* file.
* Add *Greeting.java*, *GreetingController.java*, and *MailUser.java* files to *demo/src/main/java/com/example/demo* directory.
* Move *json* file to *demo/src/main/resources directory*.
* Navigate to the path of directory **demo**.
* Run the application using the command *mvn spring-boot:run*.
* Open your default browser and use the following web-links to *get_mails* from and *set_mail* to the database.
  
  *http://localhost:8080/get_mails*
  
  *http://localhost:8080/set_mail?mail=demo@demo.com*
## Task-III
Make following changes.
* Change the *port* configuration in such a way that ordinary users cannot access certain services.
* Navigate to *demo/src/main/resources* directory.
* Add the following code to *application.properties*.
  *server.port=8081*
  *management.port=8082*
* Run the application using the command *mvn spring-boot:run*.
* Open your default browser and use the following web-link.
  *http://localhost:8081/greeting*
  
  The tutorial is available at [Medium](https://nauman-shahid.medium.com/how-to-make-a-web-application-using-spring-boot-4c89c8e7053e?sk=2b98056cea2dd973474ef3c41b91bf92).
