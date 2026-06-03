FROM tomcat:8-jre11
LABEL THis is docker app
Maintainer name Raviteja
RUN rm -rf /usr/locl/tomcat/conf/
COPY target/*.war /usr/local/tomact/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
