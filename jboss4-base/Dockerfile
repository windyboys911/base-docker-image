FROM harbor-dev.fsg.inner:8443/library/jboss4-base:latest
ENV JAVA_HOME /usr/share/jdk1.6.0_45
ENV PATH $JAVA_HOME/bin:$PATH
ENV CLASSPATH .:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
COPY run.conf /home/cloudJboss/jboss-4.2.3.GA/bin/

EXPOSE 22
EXPOSE 8080
EXPOSE 8081
CMD ./home/cloudJboss/jboss-4.2.3.GA/bin/run.sh
