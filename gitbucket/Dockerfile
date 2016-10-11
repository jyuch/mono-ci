FROM java:openjdk-8-jre-alpine

ADD https://github.com/gitbucket/gitbucket/releases/download/4.5/gitbucket.war /opt/gitbucket/gitbucket.war

VOLUME /srv/gitbucket

EXPOSE 8080

CMD ["java", "-jar", "/opt/gitbucket/gitbucket.war", "--gitbucket.home=/srv/gitbucket"]
