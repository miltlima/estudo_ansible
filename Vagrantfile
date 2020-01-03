
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

  config.vm.define "wordpress" do |m|
    m.vm.network "private_network", ip: "172.17.177.40"
    m.vm.network "public_network", ip: "0.0.0.0"
  end
  
end
