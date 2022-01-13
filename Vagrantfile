Vagrant.configure("2") do |config|
  config.vm.define "office-web-test" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-20.04"
    subconfig.vm.hostname = "office-web-test"
    #subconfig.vm.network "public_network", ip: "192.168.0.17"
    subconfig.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)"
  end

  config.vm.define "open-hrm" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-20.04"
    subconfig.vm.hostname = "open-hrm"
  end

  config.vm.define "las" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-20.04"
    subconfig.vm.hostname = "las"
  end
  
  config.vm.define "dev-machine" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-20.04"
    subconfig.vm.hostname = "dev-machine"
    subconfig.vm.network "public_network", bridge: "en0: Wi-Fi (AirPort)"
  end
end
