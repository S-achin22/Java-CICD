# Java-CICD

This project is to create a CI/CD pipeline for containerized Java applications  

You can get a demo project setup using this: https://start.spring.io/  
Get a demo.zip file on your local machine.

Write your code in folder /src/main/java  
For example System.out.println("Microservice!");

Maven Commands  
To build: mvn compile  
To build a jar file: mvn clean install  (This creates a jar file in target directory as well as .m2 directory in home)  

To build a war file you'll have to add a line into pom.xml file.  
<packaging>war</packaging>  

