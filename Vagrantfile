Vagrant.configure(2) do |config|
  config.vm.boot_timeout = 1800
  config.vm.hostname = "config.vm.hostname"
  config.vm.box = "buraksakrulu/RTTI-WS16-01-01-01"
  config.vm.box_version = "01.01.01"
  config.vm.network "private_network", brigde: "VirtualBox Host-Only Network" , ip: "192.168.56.109"
  config.vm.provider "virtualbox" do |vb|
      vb.gui = false
      vb.cpus = "2"
      vb.memory = "2048"
  end
end