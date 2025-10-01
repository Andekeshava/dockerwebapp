FROM tomcat:jdk17-temurin-noble
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy WAR from target directory built by Maven
COPY target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]


