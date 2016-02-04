FROM jenkins:latest
MAINTAINER andreasabdi

USER root
RUN mkdir -p /var/logs/jenkins
RUN chown -R jenkins:jenkins /var/logs/jenkins

USER jenkins

ENV JENKINS_OPTS="--logfile=/var/logs/jenkins/jenkins.log"
