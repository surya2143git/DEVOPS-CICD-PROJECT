# CICD-PROJECT
CICD PROJECT
This project is based on to create the Web page by the CICD work flow using with such devops tools by existing XML file.Builded it has a WAR file and using versioning. Using the middleware has TOMCAT and creating such scripted pipelin to staging in the jenkins for SCM, Integration, Testing, Deployment and Artifact repository. Using EC2 instace(t2.medium) as a server to fast working. Also using java for jenkins.
Created three EC2 instance for CICD, SONARQUBE AND NEXUS.
Give such security groups based on the tools portnumber.
Integrating this in the jenkins by pipelines, for this giving such credentials to access each other.
Installed such plugins, configured such files and also created the RDS mysql and executed it.
STAGE 1 - SCM CHECK-OUT
STAGE 2 - MAVEN-BUILD
STAGE 3 - SONARQUBE ANALYSIS
STAGE 4 - BUILD DOCKER IMAGE
STAGE 5 - PUSH DOKCER IMAGE TO DOCKER HUB
STAGE 6 - STORE DOCKER IMAGES IN NEXUS PRIVATE REGISTERY
STAGE 7 - REMOVE OLD CONTAINER BEFORE DEPLOYING INTO VM
STAGE 8- DEPLOY THE DOCKER IMAGE ON VM
Finally completed all stages with these tools.


