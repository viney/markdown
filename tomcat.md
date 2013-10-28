# <a name="0" />目录

* 1 **[目录](#0)**
* 2 **[版本](#1)**
* 3 **[JDK安装](#2)**
    - 3.1 [JDK下载](#3)
    - 3.2 [JDK安装](#4)
    - 3.3 [JDK配置](#5)
    - 3.4 [JDK验证](#6)
* 4 **[Tomcat安装](#7)**
    - 4.1 [Tomcat下载](#8)
    - 4.2 [Tomcat解压缩](#9)
    - 4.3 [Tomcat安装](#10)
    - 4.4 [Tomcat验证](#11)
* 5 **[多项目配置](#12)**
    - 5.1 [Tomcat配置多个项目](#13)
    - 5.2 [Tomcat每个项目对应唯一端口](#14)
* 6 **[HAProxy安装](#15)**
    - 6.1 [HAProxy下载](#16)
    - 6.2 [HAProxy安装](#17)
    - 6.3 [HAProxy配置](#18)

## <a name="1" />版本

> v0.1

## <a name="2" />JDK安装

### <a name="3" />JDK下载

> 下载64位JDK
> wget -c http://download.oracle.com/otn-pub/java/jdk/7u45-b18/jdk-7u45-linux-x64.rpm

### <a name="4" />JDK安装

**检查JDK信息**

> rpm -qa | grep java

**如果有openJDK,执行下面操作**

> rpm -e --nodeps java-1.6.0-openjdk-1.6.0.0-1.45.1.11.1.el6.x86_64

**安装JDK**
> rpm -ivh jdk-7u45-linux-x64.rpm

### <a name="5" />JDK配置

**配置信息写到: vim /etc/profile**

> export JAVA_HOME=/usr/java/jdk1.7.0_40

> export CLASSPATH=$CLASSPATH:.:$JAVA_HOME/lib:$JAVA_HOME/jre/lib

> export PATH=$PATH:$JAVA_HOME/bin:$JAVA_HOME/jre/bin

### <a name="6" />JDK验证

## <a name="7" />Tomcat安装

### <a name="8" />Tomcat下载

### <a name="9" />Tomcat解压缩

### <a name="10" />Tomcat安装

### <a name="11" />Tomcat验证

## <a name="12" />多项目配置

### <a name="13" />Tomcat配置多个项目

### <a name="14" />Tomcat每个项目对应唯一端口

## <a name="15" />HAProxy安装

### <a name="16" />HAProxy下载

### <a name="17" />HAProxy安装

### <a name="18" />HAProxy配置
