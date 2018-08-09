## Welcome to GitHub Pages
This Repository contain best example of multiple tomcat instances on Redhat 7 and Ubuntu servers under /app directory structure
https://github.com/amitbarai/tomcat-multi-instance

### To install tomcat install on Redhat7
comment "tomcat-install-ubuntu" in site.yml file and use role tomcat_install_redhat7

### To install tomcat install on ubuntu
comment "tomcat_install_redhat7" in site.yml file and use role "tomcat-install-ubuntu"

### To instance name and port number use below path
repo > role > rolename > var > main.yml 

### Git repo address

https://github.com/amitbarai/tomcat-multi-instance/archive/master.zip

git@github.com:amitbarai/tomcat-multi-instance.git
