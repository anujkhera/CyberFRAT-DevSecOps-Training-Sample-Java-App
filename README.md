This is a sample Java application to deliver hands-on exercises in the DevSecOps Training at [CyberFRAT](https://cyberfrat.com/event/devsecops/)

Original Author https://github.com/sebsto/webapp

Deployment Requirements

* Tomcat

Refer to Jenkinsfile to build in Jenkins

#Build Instruction

```
mvn3 clean package
```

#Deploy instruction

Deploy ```target/WebApp.war``` on Tomcat
 
#TODO
 
Add instruction to deploy to ElasticBeanstalk