FROM quay.io/wildfly/wildfly:26.1.2.Final-jdk17

RUN $JBOSS_HOME/bin/add-user.sh -u kidarraga -p kidarraga --silent

CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]