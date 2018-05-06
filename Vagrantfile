# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"


Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/bionic64"
    config.ssh.insert_key = false
    config.vm.hostname = "gahc-E580"
    # config.vm.provision "ansible" do |ansible|
    #     ansible.playbook = "./tasks/main.yml"
    # end
    config.vm.provider :virtualbox do |v|
        v.memory = 1024
    end
  end