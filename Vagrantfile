#starting with vagrant simple vagrantfile with multiple machines not multivagrant file

Vagrantfile
-----------
Vagrant.configure("2") do |config|
  # control node server
  config.vm.define "master" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-22.04-arm64"
  end
  # managed node 1
  config.vm.define "node1" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-22.04-arm64"
  end
  # managed node 2
  config.vm.define "node2" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-22.04-arm64"
  end
end




