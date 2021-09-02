# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.hostname = "focal"
  config.vm.boot_timeout = 3000
  config.vm.synced_folder ".", "/vagrant", disabled: true
  config.vm.network "public_network", ip: "192.168.1.220"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
  end
end
