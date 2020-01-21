FROM tomcat:8.5.46-jdk8-openjdk

RUN rm -Rf /usr/local/tomcat/webapps/member ## tomcat root 경로 삭제
COPY ./member-1.0.0-BUILD-SNAPSHOT.war /usr/local/tomcat/webapps/member.war