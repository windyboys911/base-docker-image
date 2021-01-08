FROM harbor-dev.fsg.inner:8443/library/tomcat7-base:latest
ENV JAVA_HOME /opt/jdk7/
ENV PATH $JAVA_HOME/bin:$PATH
ENV CLASSPATH .:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar


EXPOSE 22
EXPOSE 8080
EXPOSE 8081
CMD /opt/apache-tomcat-7.0.107/bin/catalina.sh run
