# resource
install ansible from resource
$ git clone git://github.com/ansible/ansible.git --recursive
$ cd ./ansible
$ source ./hacking/env-setup


# centos7
install ansible in centos7
```
# configure epel
# yum -y install ansible
```

# ubuntu 16
```
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible
```

# using pip
```
sudo easy_install pip
sudo pip install ansible
```

# requirements
## host node
2.6 <= python < 3
## controlled node

