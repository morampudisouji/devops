FROM tomcat:7.0
MAINTAINER dharmaraobala@gmail.com
RUN apt-get update
ADD https://excellmedia.dl.sourceforge.net/project/openmrs/releases/OpenMRS_Platform_2.0.1/openmrs.war /usr/local/tomcat/webapps/openmrs.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
