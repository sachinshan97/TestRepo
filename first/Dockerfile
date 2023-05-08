FROM centos:7
RUN yum update -y 
RUN yum install wget -y 
RUN wget https://download.oracle.com/java/17/latest/jdk-17_linux-x64_bin.rpm sudo rpm -ivh jdk-17_linux-x64_bin.rpm -y
WORKDIR jenkins
RUN wget https://updates.jenkins.io/download/war/2.403/jenkins.war -Y
CMD ["java -jar" , "jenkins.war &&"]
