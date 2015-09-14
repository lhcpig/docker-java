FROM centos:centos7
MAINTAINER lhcpig <lhcpig@qq.com>

ENV container docker
#RUN yum -y update; yum clean all
RUN yum install -y java-1.8.0-openjdk; yum clean all


ENV JAVA_HOME /usr/lib/jvm/jre
ENV LANG zh_CN.UTF-8

RUN echo "export JAVA_HOME=/usr/lib/jvm/jre" >> /etc/profile

CMD ["bash"]