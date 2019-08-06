FROM tomcat:latest
RUN apt-get update && apt-get install vim -y
ADD target/index.html $CATALINA_HOME/webapps/pd/index.html
WORKDIR $CATALINA_HOME/webapps
EXPOSE 8080
#CMD ["catalina.sh", "run"]
