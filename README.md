# install vagrant
```
$ sudo apt-get install vagrant
$ vagrant -v
```

# install virtual box
```
$ sudo apt-get install virtualbox
$ VBoxManage -v
```

# add Centos7 box
```
$ vagrant box add centos/7
==> box: Loading metadata for box 'centos/7'
    box: URL: https://vagrantcloud.com/centos/7
This box can work with multiple providers! The providers that it
can work with are listed below. Please review the list and choose
the provider you will be working with.

1) hyperv
2) libvirt
3) virtualbox
4) vmware_desktop

Enter your choice: 3
==> box: Adding box 'centos/7' (v1901.01) for provider: virtualbox
    box: Downloading: https://vagrantcloud.com/centos/boxes/7/versions/1901.01/providers/virtualbox.box
==> box: Successfully added box 'centos/7' (v1901.01) for 'virtualbox'!

$ vagrant box list
```

# init vagrant 
```
$ mkdir my_k8s
$ cd my_k8s
$ vagrant init centos/7
```

# Vagrant up
```
$ vagrant up
$ vagrant ssh master1
[vagrant@localhost ~]$ cat /etc/redhat-release 
CentOS Linux release 7.6.1810 (Core) 
```

