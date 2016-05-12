# CDH-ClouderaManager

## Install the Oracle JDK on the Cloudera Manager Server Host

### Install the JDK from a repository

```
$ sudo yum install oracle-j2sdk1.7
```

### Install the JDK manually

https://github.com/thewertzgroup/CDH-JavaDevelopmentKit

## Configure REPO Strategy

http://www.cloudera.com/documentation/enterprise/release-notes/topics/cm_vd.html

Type | Location | Repo File | Tarball File
-----|----------|-----------|-------------
yum RHEL/CentOS/Oracle 7 | https://archive.cloudera.com/cm5/redhat/7/x86_64/cm/5/ | https://archive.cloudera.com/cm5/redhat/7/x86_64/cm/cloudera-manager.repo | https://archive.cloudera.com/cm5/cm/5/cloudera-manager-centos7-cm5.7.0_x86_64.tar.gz
yum RHEL/CentOS/Oracle 6 | https://archive.cloudera.com/cm5/redhat/6/x86_64/cm/5/ | https://archive.cloudera.com/cm5/redhat/6/x86_64/cm/cloudera-manager.repo | https://archive.cloudera.com/cm5/cm/5/cloudera-manager-el6-cm5.7.0_x86_64.tar.gz
yum RHEL/CentOS/Oracle 5 | https://archive.cloudera.com/cm5/redhat/5/x86_64/cm/5/ | https://archive.cloudera.com/cm5/redhat/5/x86_64/cm/cloudera-manager.repo | https://archive.cloudera.com/cm5/cm/5/cloudera-manager-el5-cm5.7.0_x86_64.tar.gz

## Install the Cloudera Manager Server Packages

```
$ sudo yum install cloudera-manager-daemons cloudera-manager-server
```
