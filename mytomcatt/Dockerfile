FROM tomcat:8-jre8
Run apt-get update

RUN apt-get install -y postgresql-9.5

COPY dbproject.war /usr/local/tomcat/webapps/
