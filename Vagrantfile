Vagrant.configure("2") do |config|
  # CentOS 9 Stream official box
  config.vm.box = "generic/centos9s"

  # Hostname
  config.vm.hostname = "centos9-webserver"

  # Forwarded port (so you can also use localhost:8080)
  config.vm.network "forwarded_port", guest: 80, host: 8080

  # Private static IP (you can access directly via 192.168.56.10)
  config.vm.network "private_network", ip: "192.168.56.10"

  # Provisioning script
  config.vm.provision "shell", path: "setup.sh"
end
