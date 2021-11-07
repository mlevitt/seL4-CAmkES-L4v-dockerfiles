# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-20.04"
  config.vm.hostname = 'foo.bar.com'
  config.vm.provider "virtualbox" do |v|  
    v.name = "foobar"
  end
  config.vm.provision "shell",    inline: 
    "make -C /vagrant"
end
