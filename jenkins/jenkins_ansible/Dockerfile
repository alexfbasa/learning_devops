FROM jenkins/jenkins
USER root

RUN yum -y install epel-release && yum clean all
RUN yum -y install python3-pip && yum clean all
RUN pip install ansible --upgrade

