WildFly 10.1 Build and Running Image
========================================

Installation and Usage
------------------------

```
$ git clone https://github.com/sclorg/s2i-base-container.git
$ cd s2i-base-container
$ mv Dockerfile Dockerfile.tmp
$ mv Dockerfile.rhel7 Dockerfile
$ sudo docker build -t openshift/base-rhel7 .
$ cd ..
$ git clone https://github.com/taksato-redhat/wildfly-101-rhel7.git
$ cd wildfly-101-rhel7
$ sudo docker build -t openshift/wildfly-101-rhel7 .
```
