Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.box_download_insecure=true
  config.vm.provider "virtualbox" do |v|
    v.name = "vagrant-ubuntu"
    v.memory = 1024
    v.cpus = 01
  end

config.vm.network "public_network"

config.vm.synced_folder "projeto01/", "/var/www/html"
  
end

