FROM jboss/wildfly
USER root

EXPOSE 8080
EXPOSE 9990

RUN /opt/jboss/wildfly/bin/add-user.sh admin 4me4u2 --silent
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]


RUN yum -y install nano
RUN export TERM=xterm
