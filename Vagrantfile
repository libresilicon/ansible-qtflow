# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "16768"
    vb.cpus = "8"
  end

  config.vm.box = "ubuntu/bionic64"
  
  config.vm.provision "shell", inline: "apt install -y python"
  
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "install.yml"
  end

end
