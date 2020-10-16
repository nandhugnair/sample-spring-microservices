FROM tomcat:8.0-alpine
LABEL maintainer="gnairnandhu@gmail.com"
ADD target/customer-service.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]


