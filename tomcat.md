# 目录

* 1 **[目录](#toc_0)**
* 2 **[版本](#toc_1)**
* 3 **[JDK安装](#toc_2)**
    - 3.1 [JDK下载](#toc_3)
    - 3.2 [JDK安装](#toc_4)
    - 3.3 [JDK配置](#toc_5)
    - 3.4 [JDK验证](#toc_6)
* 4 **[Tomcat安装](#toc_7)**
    - 4.1 [Tomcat下载](#toc_8)
    - 4.2 [Tomcat解压缩](#toc_9)
    - 4.3 [Tomcat安装](#toc_10)
    - 4.4 [Tomcat验证](#toc_11)
* 5 **[多项目配置](#toc_12)**
    - 5.1 [Tomcat配置多个项目](#toc_13)
    - 5.2 [Tomcat每个项目对应唯一端口](#toc_14)
* 6 **[HAProxy安装](#toc_15)**
    - 6.1 [HAProxy下载](#toc_16)
    - 6.2 [HAProxy安装](#toc_17)
    - 6.3 [HAProxy配置](#toc_18)

## 版本

> v0.1

## JDK安装

### JDK下载

> 下载64位JDK
> wget -c http://download.oracle.com/otn-pub/java/jdk/7u45-b18/jdk-7u45-linux-x64.rpm

### JDK安装

**检查JDK信息**

> rpm -qa | grep java

**如果有openJDK,执行下面操作**

> rpm -e --nodeps java-1.6.0-openjdk-1.6.0.0-1.45.1.11.1.el6.x86_64

**安装JDK**
> rpm -ivh jdk-7u45-linux-x64.rpm

### JDK配置

**配置信息写到: vim /etc/profile**

> export JAVA_HOME=/usr/java/jdk1.7.0_40

> export CLASSPATH=$CLASSPATH:.:$JAVA_HOME/lib:$JAVA_HOME/jre/lib

> export PATH=$PATH:$JAVA_HOME/bin:$JAVA_HOME/jre/bin

### JDK验证

## Tomcat安装

### Tomcat下载

### Tomcat解压缩

### Tomcat安装

### Tomcat验证

## 多项目配置

### Tomcat配置多个项目

### Tomcat每个项目对应唯一端口

## HAProxy安装

### HAProxy下载

### HAProxy安装

### HAProxy配置
