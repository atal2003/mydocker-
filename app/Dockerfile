FROM tomcat:8-jre11
RUN  rm -rf  /usr/local/tomcat/webapps/*
COPY vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat
LABEL "Authur"="Atal"
LABEL "Project"="Atal_project"