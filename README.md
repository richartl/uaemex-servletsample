# Basic Servlet Sample
## UAEMEX Texcoco

### Requirements to run this project
* Docker
* Maven
* Java

### Running project
First of all you have to compile with maven
```
mvn clean
mvn compile
mvn package
```

You can see new folder named target and a war file inside it called ServletSample.war.
So you have to build docker imaage and after that you will be able to create container to check this project

```
docker build -t <name-of-image> .
docker run -it --rm -p 8081:8080 <name-of-image>
```
With this steps you will be able to check this project on localhost:8081/ServletSample in your browser
