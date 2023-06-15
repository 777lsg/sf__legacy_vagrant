
Vagrant.configure("2") do |config|
  
  config.vm.define "ubuntu2204"
  config.vm.box = "ubuntu2204"
  config.vm.box_url = 'file:///E:/!VM/vagrant/package.box'
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = 1
  end

  config.vm.provision "shell", inline: <<-SHELL
    sudo apt-get update
  SHELL
  
end
