Vagrant.configure("2") do |config|
  config.vm.define "host1" do |host1|
    host1.vm.box = "debian/bullseye64"
    host1.vm.network "private_network", type: "static", ip: "192.168.56.10"
  end
  config.vm.define "host2" do |host2|
    host2.vm.box = "debian/bullseye64"
    host2.vm.network "private_network", type: "static", ip: "192.168.56.11"
  end
end
