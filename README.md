# docker-rhel-clones
Sources to build RHEL (or CentOS) clones. *[Apache-2.0]*

# Official IBM - RedHat Enterprise Linux (RHEL) Versions

## Current versions

| Date Release RHEL (Last) |RHEL Version (Last) |Kernel|
|-------------------|------------|--------------|
|2022-05-17 (2023-05-10)|9  (9.2)    |5.14.0-70.13.1.el9_0 (5.14.0-284.11.1.el9_2)|
|2019-05-07 (2023-05-16)|8  (8.8)    |4.18.0-80 (4.18.0-477.10.1.el8_8)|

## Obsolete versions

| Date Release RHEL (Last) |RHEL Version (Last) |Kernel|
|-------------------|------------|--------------
|2013-12-11 (2020-09-29) |7  (7.9)    |3.10.0-54.0.1 (3.10.0-1160)|
|2010-11-09 (2018-06-19) |6  (6.10)   |2.6.32-71 (2.6.32-754)|
|2007-03-15 (2014-09-16)|5 (5.11) |2.6.18-8 (2.6.18-398)|

## Links
- [Website](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux)
- [RHEL Releases](https://access.redhat.com/articles/3078)

# Clones and derivative versions

## Version 9
- **Alma Linux 9.2**:  `docker pull almalinux:9.2` - *minimal*: `docker pull almalinux:9.2-minimal`
- **Rocky Linux 9.2**:  `docker pull rockylinux:9.2` - *minimal*: `docker pull rockylinux:9.2-minimal`
- **Oracle Linux 9.2**: `docker pull oraclelinux:9` - *slim*: `docker pull oraclelinux:9-slim`
- **Euro Linux 9**: `docker pull eurolinux/eurolinux-9` 

## Version 8
- **Alma Linux 8.8**: `docker pull almalinux:8.8` - *minimal*: `docker pull almalinux:8.8-minimal`
- **Rocky Linux 8.8**: `docker pull rockylinux:8.8` - *minimal*: `docker pull rockylinux:8.8-minimal`
- **Oracle Linux 8.8**: `docker pull oraclelinux:8.8` - *slim*: `docker pull oraclelinux:8-slim`
- **Euro Linux 8** : `docker pull eurolinux/eurolinux-8`
- **CentOS 8 (EuroLinux)** : `docker pull eurolinux/centos-8`
- **CentOS 8 (USTC Mirror)** : `docker pull ustclug/centos:8`

## Version 7
- **Oracle Linux 7.9**: `docker pull oraclelinux:7.9` - *slim*: `docker pull oraclelinux:7-slim`
- **Euro Linux 7** : `docker pull eurolinux/eurolinux-7`
- **Scientific Linux 7 (Official)**: `docker pull sl:7`
- **Scientific Linux 7 (EuroLinux)** : `docker pull eurolinux/scientific-linux-7`
- **CentOS 7 (EuroLinux)** : `docker pull eurolinux/centos-7`
- **CentOS 7.9 (Official)** : [Docker Hub](https://hub.docker.com/_/centos): `docker pull centos:centos7.9.2009`
- **CentOS 7.9 (USTC Mirror)**: docker pull ustclug/centos:7.9.2009

## Version 6
- **Oracle Linux 6.10**: `docker pull oraclelinux:6.10`
- **Euro Linux 6** : `docker pull eurolinux/eurolinux-6`
- **Scientific Linux 7 (Official)**: `docker pull sl:6`
- **Scientific Linux 6 (EuroLinux)** : `docker pull eurolinux/scientific-linux-6`
- **CentOS 6 (EuroLinux)** : `docker pull eurolinux/centos-6`
- **CentOS 6.10 (USTC Mirror)**: `docker pull ustclug/centos:6.10`

## Version 5
- **Oracle Linux 5.11**: `docker pull oraclelinux:5.11`
- **CentOS 5.11 (USTC Mirror)**: `docker pull ustclug/centos:5.11`

# Details of Clones and Derivatives

## AlmaLinux
- Objective : completely binary compatible fork of RHEL
- Offers commercial support

### Current Versions
- [ISOs Download](https://mirrors.almalinux.org/isos.html)
- [DockerHub](https://hub.docker.com/_/almalinux)
- **latest**: `docker pull almalinux:latest`
- **minimal**: `docker pull almalinux:minimal`

### Links
- [Website](https://distrowatch.com/table.php?distribution=alma)
- [Distrowatch Page](https://distrowatch.com/table.php?distribution=alma)

## RockyLinux
- Objective : 100% bug-to-bug compatible with RHEL.
- Offers commercial support

### Current versions
- [ISOs Download](https://rockylinux.org/download/)
- [DockerHub](https://hub.docker.com/_/rockylinux)

### Links
- [Website](https://rockylinux.org/)
- [Distrowatch Page](https://distrowatch.com/table.php?distribution=rocky)

## Eurolinux
- Started 2013
- Based in Poland
- Offers commercial support
- [EuroELS – support for Enterprise Linux 6](https://en.euro-linux.com/eurolinux/euroels/): Commercial support until mid-2024

### Current versions
- [ISOs Download](https://en.euro-linux.com/eurolinux/download/)
- [DockerHub](https://hub.docker.com/_/eurolinux)

### Links
- [Website](https://en.euro-linux.com/)
- [Distrowatch Page](https://distrowatch.com/table.php?distribution=eurolinux)

## OracleLinux
- Backed by Oracle
- Custom kernel: "Oracle Unbreakable Kernel"
- Offers commercial support

### Current versions
- [ISOs Download](https://yum.oracle.com/oracle-linux-isos.html)
- [DockerHub](https://hub.docker.com/_/oraclelinux)

### Links
- [Website](https://www.oracle.com/linux/)
- [Distrowatch Page](https://distrowatch.com/table.php?distribution=oraclelinux)

## Springdale Linux
- Backed by Princeton University and the Institute for Advanced Study
- University-backed, no commercial support
 
### Current versions
- [ISOs Download](https://springdale.math.ias.edu/)
- Offers Boot/PXE ISO versions for i386 and x86_64 : 5.11, 6.10, 7.9, 8.8, 9.2
- Offers CD/DVD ISO versions for i386 and x86_64 : 6.6/6.8 and 7.3/7.9
- Offers YM repositories for version: 1, 2, 5, 6, 7, 8, 9

### Links
- [Website - Princeton University](https://springdale.math.ias.edu/)
- [Distrowatch Page](https://distrowatch.com/table.php?distribution=springdale)

## Scientific Linux
- [Website](https://scientificlinux.org/): Latest: 7.9 (2020)
- [DockerHub](https://hub.docker.com/_/sl)

## University of Science and Technology of China (USTC)
- [Website](https://lug.ustc.edu.cn/)
- [DockerHub](https://hub.docker.com/u/ustclug)
- [CentOS Mirror](https://mirrors.ustc.edu.cn/centos/): >= CentOS 2
- [Fedora Mirror](https://mirrors.ustc.edu.cn/fedora/releases/): >= Fedora 7
- [Scientific Linux Mirror](https://mirrors.ustc.edu.cn/scientificlinux/): >= Scientific Linux 7
- [Rocky Linux Mirror](https://mirrors.ustc.edu.cn/rocky/)>= Rocky Linux 8.4

----
Updated: 2023-10-15
 
