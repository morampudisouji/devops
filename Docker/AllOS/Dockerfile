FROM ubuntu:trusty
MAINTAINER Dharmaraobala@gmail.com
RUN apt-get update
ADD Hi.txt /Hi.txt
CMD ["/bin/bash"]





"opensource shopping cart java"

Take any java opensource application, php application 
I want you to build a docker image, 
run that on a single host machine. and then try to run the same in a cluster. 

openmrs
opencart
shopify
orazgehrm

open any of this site, try to see their installation steps.
Try to write a docker file around it.


dockercontrainer
host it in a singel machine
and hten host it in cluster.


FROM ubuntu:trusty
MAINTAINER a
RUN apt-get update && apt-get install apache2 && apt-get service start
EXPOSE 80
CMD ["ping" , "google.com"]

----
FROM ubuntu:trusty
MAINTAINTER a
RUN apt-get update
ADD Hi.txt /hi.txt
CMD ["/bin/bash"]
----
FROM ubuntu:trusty
MAINTAINTER a
RUN apt-get update
ADD https://codeload.github.com/asquarezone/DockerZone/zip/master /master
CMD ["/bin/bash"]
-----
"Puppet agent download"
	puppet agent |ubuntu 14.04
https://pm.puppetlabs.com/puppet-agent/2017.1.1/1.9.3/repos/deb/xenial/PC1/puppet-agent_1.9.3-1xenial_i386.deb
FROM ubuntu:trusty
MAINTAINTER a
RUN apt-get update
ADD https://pm.puppetlabs.com/puppet-agent/2017.1.1/1.9.3/repos/deb/xenial/PC1/puppet-agent_1.9.3-1xenial_i386.deb /https://pm.puppetlabs.com/puppet-agent/2017.1.1/1.9.3/repos/deb/xenial/PC1/puppet-agent_1.9.3-1xenial_i386.deb
CMD ["/bin/bash"]

----
OpenMRS
FROM tomcat:7
ADD  https://downloads.sourceforge.net/project/openmrs/releases/OpenMRS_Platform_2.0.4.1/openmrs.war /usr/local/tomcat/webapps/openmrs.war
EXPOSE 8080
#RUN service tomcat7 restart
CMD ["bin/catalina.sh","run"]
----
docker run -p 8081:8080 -d tomcat_demo:openmrs
----
docker build -t first:1.0 . (dot)
docker iamges
docker run -it second:1.0
docker run -it/-d -p 8081:80 first:1.0
cat /Hi.txt
----
to download from the web
docker ps
docker stop 60e1*** (container id/name)
lets stop all the containers

https://codeload.github.com/shopizer-ecommerce/shopizer/zip/2.0.5

https://codeload.github.com/asquarezone/DockerZone/zip/master
----
hub.docker.com
	tomcat 7
let's just run this image,no need to build it.

docker run -it tomcat:7.0 /bin/bash
ls
where do i need to deploy /usr/local/tomcat/webapps
to this location we need to copy war files.
----
Jenkins
FROM tomcat:7
MAINTAINER a
ADD  http://mirrors.jenkins.io/war-stable/latest/jenkins.war /usr/local/tomcat/webapps/jenkins.war
EXPOSE 8080
#RUN service tomcat7 restart
CMD ["catalina.sh","run"]
----
Now i need to start the container. when ever you are taking the base containers , which are applications, try to copy the exact statement from them it self,
when it comes to CMD. they might have done some plumbing around it, where your application runs in the background.


docker build -t  tomcat_demo:jenkins
docker images

I want to run this container in the background, this application i want to run it forever, untill and unless you stop it, you want to run it.
To run in the back ground, we have detached mode
docker run -p 80:8080 -d tomcat_demo:jenkins
 ec2 host 80 mapped with container 8080 port
----
FROM ubuntu:trusty
MAINTAINTER a
WORKDIR /tmp
RUN apt-get update
ADD https://codeload.github.com/asquarezone/DockerZone/zip/master /master
CMD ["/bin/bash"]
----
FROM ubuntu:trusty
RUN apt-get update
ENTRYPOINT echo
CMD ["hello"]
---

When you don't have a entry point, what ever you have written in cmd will be executed	

FROM ubuntu:trusty
RUN apt-get update
ENTRYPOINT ping
CMD ["google.com"]

You can override cmd from external world. you can't override entrypoint.
Whenever you want to create a container where you dont' want you usr to conrol what application has to be started, but you just want to give your user 
an option so taht he set multiple arguments.


Scratch is core linux kerel. If you want to build any conrainer from beging, FROM scratch ...
18th april , last 10 minutes pending.























