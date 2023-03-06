# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "generic/debian11"
  config.vm.hostname = "dockerhost"
  config.vm.define "dockerhost"
  config.vm.provider "vmware_desktop" do |vb|
	vb.gui = true
	#vb.name = "vagrant_vm"
	vb.memory = "1024"
    vb.cpus = 1
  end
  config.vm.provision "shell", privileged: false, path: "./setup.sh"
end
