# GRyCAP repository
GRyCAP Ubuntu and RHEL packages repository

# Configure GRyCAP repository

## RHEL derivatives

Import repository key:
```sh
rpm --import https://raw.githubusercontent.com/grycap/package-repos/refs/heads/main/centos/keyFile
```

Add repository file:
```sh
wget https://raw.githubusercontent.com/grycap/package-repos/refs/heads/main/centos/10/grycap.repo -O /etc/yum.repos.d/grycap.repo
```

## Ubuntu

Import repository key:
```sh
wget https://raw.githubusercontent.com/grycap/package-repos/refs/heads/main/ubuntu/keyFile -O /etc/apt/trusted.gpg.d/grycap.asc
```

Install repository list file (use 20, 22 or 24 version number):
```sh
wget https://raw.githubusercontent.com/grycap/package-repos/refs/heads/main/ubuntu/grycap-ubuntu24.list -O /etc/apt/sources.list.d/grycap.list
```

