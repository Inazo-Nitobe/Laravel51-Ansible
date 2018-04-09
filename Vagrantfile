Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-6.7-i386"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.synced_folder "./data", "/vagrant_data", :mount_options => ['dmode=777', 'fmode=777']
end
