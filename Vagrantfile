Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.network "private_network", ip: "192.168.17.21"
  config.vm.network "forwarded_port", guest: 5432, host: 5432
end
