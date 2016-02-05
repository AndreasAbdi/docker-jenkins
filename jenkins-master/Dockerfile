FROM jenkins:1.609.1
MAINTAINER andreasabdi

USER root
RUN mkdir -p /var/logs/jenkins
RUN mkdir -p /var/cache/jenkins
RUN chown -R jenkins:jenkins /var/logs/jenkins
RUN chown -R jenkins:jenkins /var/cache/jenkins

USER jenkins

ENV JENKINS_OPTS="--logfile=/var/logs/jenkins/jenkins.log --webroot=/var/cache/jenkins/war"
