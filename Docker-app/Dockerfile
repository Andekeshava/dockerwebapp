FROM tomcat:9.0.89-jdk17-temurin-jammy
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy WAR from target directory built by Maven
COPY . /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]


