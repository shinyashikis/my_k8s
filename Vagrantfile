# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.define :master1 do |node|
    node.vm.network :private_network, ip: "192.168.33.21"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :master2 do |node|
    node.vm.network :private_network, ip: "192.168.33.22"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :master3 do |node|
    node.vm.network :private_network, ip: "192.168.33.23"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :minion1 do |node|
    node.vm.network :private_network, ip: "192.168.33.31"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :minion2 do |node|
    node.vm.network :private_network, ip: "192.168.33.32"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :minion3 do |node|
    node.vm.network :private_network, ip: "192.168.33.33"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :minion4 do |node|
    node.vm.network :private_network, ip: "192.168.33.34"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :minion5 do |node|
    node.vm.network :private_network, ip: "192.168.33.35"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
  config.vm.define :manage1 do |node|
    node.vm.network :private_network, ip: "192.168.33.41"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
    end
  end
end
