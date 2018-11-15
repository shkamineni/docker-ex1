FROM 		tomcat:8.0.21-jre8

COPY 		./software/ /usr/local/tomcat/webapps/

RUN apt-get update && apt-get install -y wget git-core maven

#RUN apt-get update 
#RUN apt-get install -y git
#RUN git config --global http.sslverify false

#CMD mkdir ~/.ssh
#CMD ~/.ssh
#RUN touch known_hosts
#RUN ssh-keyscan github.com >> known_hosts
#RUN cd /home
#RUN rm -rf spring-petclinic
#RUN git clone https://github.com/spring-projects/spring-petclinic.git /usr
#CMD cd spring-petclinic
#CMD ./mvnw package
#CMD java -jar target/*.jar
