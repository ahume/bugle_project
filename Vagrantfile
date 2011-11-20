Vagrant::Config.run do |config|

  config.vm.box = "lucid32"

  config.vm.box_url = "http://files.vagrantup.com/lucid32.box"

  config.vm.forward_port("web", 80, 4567)

  # Assign this VM to a host only network IP, allowing you to access it
  # via the IP.
  config.vm.network "33.33.33.10"
  
end