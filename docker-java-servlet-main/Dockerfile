FROM tomcat:9.0.58-jdk17-openjdk-slim
RUN rm -rf /usr/local/tomcat/webapps/ROOT
RUN rm -rf /usr/local/tomcat/webapps/examples
ADD docker-java-servlet-main/com.src.war /usr/local/tomcat/webapps/

EXPOSE 8080
CMD ["catalina.sh", "run"]
cmd sudo tail -f / opt / tomcat / log / catalina.out