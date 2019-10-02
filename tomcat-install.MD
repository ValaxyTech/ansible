## Tomcat8 server installation 

### Pre-requisites 
EC2 instance with port 8080

1. Install java
   ```sh
   yum install java
   ```
   
1. download tomcat8 onto /usr/local from https://tomcat.apache.org/download-80.cgi
   ```sh
   wget http://mirrors.estointernet.in/apache/tomcat/tomcat-8/v8.5.46/bin/apache-tomcat-8.5.46.tar.gz -P /usr/local
   ```
   
1. extract apache tar.gz file
   ```sh
   tar -xvzf /usr/local/apache-tomcat-8.5.46.tar.gz
   ```
   
1. start tomcat services
   ```sh
   cd /usr/local/apache-tomcat-8.5.46/bin
   ./start.sh
   ```
