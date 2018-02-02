WSL Developer Setup
===================

Get started writing Python & Java in Linux using WSL

### Update your Linux environment

```bash
$ sudo apt-get update
$ sudo apt-get upgrade
```

### Install Python tooling

```bash
$ sudo apt-get install python3
$ sudo apt-get install python3-pip
$ sudo apt-get install python-pip
$ pip3 install boto3 --user
$ pip3 install bs4 --user
$ pip3 install PyYAML --user
$ pip install boto3 --user
$ pip install bs4 --user
$ pip install PyYAML --user
```

### Install developer tooling

```bash
$ sudo add-apt-repository ppa:webupd8team/java
$ sudo apt-get install oracle-java8-installer
$ sudo apt-get install default-jdk
$ sudo apt-get install maven
$ sudo apt-get install unzip
$ sudo apt-get install p7zip
```

### Allows you to run Windows programs from your bash shell

```bash
$ sudo apt-get install realpath
```

### Install AWS tooling

```bash
$ pip3 install awscli --user
$ wget https://releases.hashicorp.com/terraform/0.9.11/terraform_0.9.11_linux_amd64.zip
$ unzip terraform_0.9.11_linux_amd64.zip
$ sudo mv terraform /usr/bin/
```

### Create a .bash_profile for personal configuration

```bash
$ (echo 'export PATH=~/.local/bin:$PATH'; echo "alias start='explorer.exe'") > ~/.bash_profile
```