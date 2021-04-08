Vagrant.configure("2") do |config|

  config.vm.box = "mrlesmithjr/bionic64-desktop"
  config.vm.synced_folder ".", "/home/vagrant/lab3"
  config.vm.provision :shell, path: "https://gist.githubusercontent.com/khale/7d51ad84dd6ac3e087b27a1cc88ab479/raw/957c86d568ee26f6525293436df8e25924cca1c2/3503-bootstrap.sh"

  config.vm.provider "vmware_desktop" do |v|
    v.gui = true
  end

  config.vm.provider "virtualbox" do |v|
    v.gui = true
  end

end
