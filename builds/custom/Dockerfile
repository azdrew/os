FROM registry.access.redhat.com/redhat-openjdk-18/openjdk18-openshift:latest
RUN echo 'copying...'
COPY test.txt /usr/local
RUN echo 'done'
RUN ls /usr/local
RUN ls ${HOME}/.m2/settings.xml
RUN cat ${HOME}/.m2/settings.xml
