FROM jenkins/jenkins
USER root
RUN apt-get update
RUN apt-get install -y python3-pip
RUN apt install sshpass
# Install app dependencies
RUN pip install --upgrade pip
RUN pip install ansible --upgrade
USER jenkins