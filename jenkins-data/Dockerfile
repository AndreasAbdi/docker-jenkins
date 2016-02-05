FROM debian:jessie
MAINTAINER andreasabdi

RUN useradd -d "/var/jenkins_home" -u 1000 -m -s /bin/bash jenkins

RUN mkdir -p /var/logs/jenkins
RUN chown -R jenkins:jenkins /var/logs/jenkins

VOLUME ["/var/logs/jenkins"]

USER jenkins

CMD ["echo", "Data container for jenkins"]
