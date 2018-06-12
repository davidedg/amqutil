For information about amqutil, please see:

http://kevinboone.net/README_amqutil.html

### Build pre-requisites on Ubuntu 16.04

```sh
$ sudo add-apt-repository -y ppa:webupd8team/java
$ sudo apt update
$ sudo apt -y dist-upgrade
$ sudo apt -y install build-essential
$ sudo apt -y install oracle-java8-installer
$ sudo apt -y install oracle-java8-set-default
$ sudo apt -y install oracle-java8-unlimited-jce-policy
$ sudo apt -y install maven git-core
$ sudo apt autoremove
```

### Build on Ubuntu 16.04
```sh
$ git clone https://github.com/davidedg/amqutil.git
$ cd amqutil
$ mvn package
```
