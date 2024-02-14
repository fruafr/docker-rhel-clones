# docker-rhel-clones
Links to RHEL (or CentOS) clones and their docker files. *[Apache-2.0]*

- [Official IBM - RedHat Enterprise Linux (RHEL) Versions](#official-ibm---redhat-enterprise-linux-rhel-versions)
- [List of clones and derivative versions for Docker/Podman](#list-of-clones-and-derivative-versions-for-dockerpodman)
- [Details of Clones and Derivatives](#details-of-clones-and-derivatives)

# Official IBM - RedHat Enterprise Linux (RHEL) Versions

## Current versions

| Date Release RHEL (Last) |RHEL Version (Last) |Kernel|
|-------------------|------------|--------------|
|2022-05-17 (2023-11-07)|9  (9.3)    |5.14.0-70.13.1.el9_0 (5.14.0-362.8.1.el9_3)|
|2019-05-07 (2023-11-14)|8  (8.9)    |4.18.0-80 (4.18.0-513.5.1.el8_9)|

## Obsolete versions

| Date Release RHEL (Last) |RHEL Version (Last) |Kernel|
|-------------------|------------|--------------
|2013-12-11 (2020-09-29) |7  (7.9)    |3.10.0-54.0.1 (3.10.0-1160)|
|2010-11-09 (2018-06-19) |6  (6.10)   |2.6.32-71 (2.6.32-754)|
|2007-03-15 (2014-09-16)|5 (5.11) |2.6.18-8 (2.6.18-398)|

## Links
- [Website](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux)
- [RHEL Releases](https://access.redhat.com/articles/3078)

# List of clones and derivative versions for Docker/Podman

## Version 9
- **AlmaLinux 9.3**:  `docker pull almalinux:9.3` - *minimal*: `docker pull almalinux:9.3-minimal`
- **RockyLinux 9.3**:  `docker pull rockylinux:9.3` - *minimal*: `docker pull rockylinux:9.3-minimal`
- **OracleLinux 9.3**: `docker pull oraclelinux:9` - *slim*: `docker pull oraclelinux:9-slim`
- **EuroLinux 9**: `docker pull eurolinux/eurolinux-9` or `docker pull quay.io/eurolinux/eurolinux-9`

## Version 8
- **AlmaLinux 8.9**: `docker pull almalinux:8.9` - *minimal*: `docker pull almalinux:8.9-minimal`
- **RockyLinux 8.9**: `docker pull rockylinux:8.9` - *minimal*: `docker pull rockylinux:8.9-minimal`
- **OracleLinux 8.8**: `docker pull oraclelinux:8.9` - *slim*: `docker pull oraclelinux:8-slim`
- **EuroLinux 8** : `docker pull eurolinux/eurolinux-8` or `docker pull quay.io/eurolinux/eurolinux-8`
- **CentOS 8.4 (Official - quay.io)**: `docker pull quay.io/centos/centos8` or `docker pull quay.io/centos/8.4.2105`
- **CentOS 8 (EuroLinux)** : `docker pull eurolinux/centos-8` or `docker pull quay.io/eurolinux/centos-8`
- **CentOS 8 (USTC Mirror)** : `docker pull ustclug/centos:8`

## Version 7
- **OracleLinux 7.9**: `docker pull oraclelinux:7.9` - *slim*: `docker pull oraclelinux:7-slim`
- **EuroLinux 7** : `docker pull eurolinux/eurolinux-7` or `docker pull quay.io/eurolinux/eurolinux-7`
- **CentOS 7 (EuroLinux)** : `docker pull eurolinux/centos-7` or `docker pull quay.io/eurolinux/centos-7`
- **CentOS 7.9 (Official)** : `docker pull centos:centos7.9.2009`
- **CentOS 7.9 (Official - quay.io)**:  `docker pull quay.io/centos/centos7` or `docker pull quay.io/centos/centos7.9.2009`
- **CentOS 7.9 (USTC Mirror)**: docker pull ustclug/centos:7.9.2009
- **Scientific Linux 7 (Official)**: `docker pull sl:7`
- **Scientific Linux 7 (EuroLinux)** : `docker pull eurolinux/scientific-linux-7`
  
## Version 6
- **OracleLinux 6.10**: `docker pull oraclelinux:6.10`
- **EuroLinux 6** : `docker pull eurolinux/eurolinux-6` 
- **Scientific Linux 6 (Official)**: `docker pull sl:6`
- **Scientific Linux 6 (EuroLinux)** : `docker pull eurolinux/scientific-linux-6`
- **CentOS 6 (Official - quay.io)**:  `docker pull quay.io/centos/centos6`
- **CentOS 6 (EuroLinux)** : `docker pull eurolinux/centos-6`
- **CentOS 6 (EuroLinux)** : `docker pull eurolinux/centos-6`
- **CentOS 6.10 (USTC Mirror)**: `docker pull ustclug/centos:6.10`

## Version 5
- **Oracle Linux 5.11**: `docker pull oraclelinux:5.11`
- **CentOS 5.11 (USTC Mirror)**: `docker pull ustclug/centos:5.11`

# Details of Clones and Derivatives

- [AlmaLinux](#almalinux)
- [RockyLinux](#rockylinux)
- [EuroLinux](#eurolinux)
- [OracleLinux](#oraclelinux)
- [Springdale Linux (Princeton/IAS)](#springdate-linux)
- [Defunct](#defunct)
- [University of Science and Technology of China (USTC) - Mirror](#university-of-science-and-technology-of-china-ustc) 

## AlmaLinux
- Objective : completely binary compatible fork of RHEL
- Offers commercial support

### Current Versions
- [ISOs Download](https://mirrors.almalinux.org/isos.html)
- [DockerHub](https://hub.docker.com/_/almalinux)
- [Quay.io](https://quay.io/repository/almalinux/almalinux)
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
- [Quay.io](https://quay.io/organization/eurolinux)

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

## Defunct

### CentOS
- Latest: 7.2009 (EOL: 2024-06-30)
- [Website](https://www.centos.org/centos-linux/)
- [Docker Hub](https://hub.docker.com/_/centos)
- [Quay.io](https://quay.io/repository/centos/centos)

### Scientific Linux 
- Latest: 7.9 (2020)
- [Website](https://scientificlinux.org/)
- [DockerHub](https://hub.docker.com/_/sl)

## University of Science and Technology of China (USTC)
- [Website](https://lug.ustc.edu.cn/)
- [DockerHub](https://hub.docker.com/u/ustclug)
- [CentOS Mirror](https://mirrors.ustc.edu.cn/centos/): >= CentOS 2
- [Fedora Mirror](https://mirrors.ustc.edu.cn/fedora/releases/): >= Fedora 7
- [Scientific Linux Mirror](https://mirrors.ustc.edu.cn/scientificlinux/): >= Scientific Linux 7
- [Rocky Linux Mirror](https://mirrors.ustc.edu.cn/rocky/)>= Rocky Linux 8.4

----
Updated: 2024-02-14
 
