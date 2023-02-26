# Overview
Spring boot web application template provides several templates for making development easier and faster

## Required Dependencies
To avoid errors that may occur during development

### White label error
```xml
<dependency>
    <groupId>org.apache.tomcat</groupId>
    <artifactId>tomcat-jasper</artifactId>
    <version>10.1.5</version>
</dependency>
```

### Javax servlet missing / not found
```xml
<dependency>
    <groupId>javax.servlet</groupId>
    <artifactId>javax.servlet-api</artifactId>
    <version>4.0.1</version>
    <scope>provided</scope>
</dependency>
```

### JSTL core error / missing dependencies (Jakarta Version)
[Download jar](https://github.com/Clouza/spring-web-app/raw/master/src/main/webapp/WEB-INF/lib/jakarta.servlet.jsp.jstl-api-2.0.0.jar)
```xml
<dependency>
    <groupId>org.glassfish.web</groupId>
    <artifactId>jakarta.servlet.jsp.jstl</artifactId>
</dependency>
```

## Contributing
Contribution is open to anyone
