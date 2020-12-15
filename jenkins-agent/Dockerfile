FROM centos:7
MAINTAINER moremagic <guowei@fsg.com.cn>
RUN yum -y update
RUN yum install -y passwd openssh-server openssh-clients initscripts java-1.8.0-openjdk java-1.8.0-openjdk-devel git which vim curl
RUN git config --global http.sslVerify false

RUN echo 'root:abc123' | chpasswd
RUN /usr/sbin/sshd-keygen

EXPOSE 22
CMD /usr/sbin/sshd -D
