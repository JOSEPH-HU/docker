FROM centos:centos7
 
MAINTAINER joseph "hlw_201304@163.com"
 
WORKDIR /opt/java

ADD jdk-8u161-linux-x64.tar.gz /opt/java

ENV JAVA_HOME=/opt/java/jdk1.8.0_161
ENV CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
ENV PATH=$JAVA_HOME/bin:$PATH

CMD ["java","-version"]
