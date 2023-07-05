# Below is the base image I will be using from Docker Registry
FROM ubuntu:22.04 

# Update all the packages on the ubuntu machine
RUN apt-get update


# Install nginx, zip, and curl. 
#   -nginx is a web server which will be used to host our game on the browser
#   -zip will be used to zip and unzip files
#   -curl enables data exchange/transfer.
RUN apt-get install -y nginx zip curl

# Used to configure nginx. Once above packages are installed, below configuration will execute in the conf file
RUN echo "daemon off;" >>/etc/nginx/nginx.conf

# Curl the repo on the given path, install all the files/packages onto the master.zip path
RUN curl -o /var/www/html/master.zip -L https://codeload.github.com/gabrielecirulli/2048/zip/master

# Unzip master folder and move all the content to the html folder. Delete the original master.zip
RUN cd /var/www/html/ && unzip master.zip && mv 2048-master/* . && rm -rf 2048-master master.zip

#Expose command is used to specify the port to be exposed for the docker container
EXPOSE 80

# Run command to start nginx
CMD ["/usr/sbin/nginx", "-c", "/etc//nginx/nginx.conf"]