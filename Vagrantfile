Vagrant.configure("2") do |config|
  config.vm.box = "slavrd/xenial64"
  config.vm.hostname = "bananas3"
  config.vm.provision "shell", path: "scripts/install_nginx.sh"
end
