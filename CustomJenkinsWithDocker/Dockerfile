     FROM jenkins/jenkins:lts
    USER root
    RUN apt-get update -qq \
        && apt-get install -qqy apt-transport-https ca-certificates curl gnupg2 software-properties-common
    RUN apt install docker.io -y
    RUN usermod -aG docker jenkins
