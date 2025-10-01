FROM tomcat:9.0.89-jdk17-temurin-jammy

# Remove default webapps
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy the WAR file as ROOT.war
COPY ROOT.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]



