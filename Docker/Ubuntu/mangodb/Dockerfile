# Set the base image to Ubuntu
From ubuntu
# File Author / Maintainer
MAINTAINER morampudisouji@gmail.com
# Update the repository sources list
Run apt-get update
################## BEGIN INSTALLATION ######################
# Install MongoDB Following the Instructions at MongoDB Docs
## Ref: http://docs.mongodb.org/manual/tutorial/install-mongodb-on-ubuntu/
# Add the package verification key
RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 7F0CEB10
# Add MongoDB to the repository sources list
RUN echo 'deb http://downloads-distro.mongodb.org/repo/ubuntu-upstart dist 10ge$
# Update the repository sources list once more
RUN apt-get update
# Install MongoDB package (.deb)
RUN apt-get install -y mongodb-10gen
# Create the default data directory
RUN mkdir -p /data/db

