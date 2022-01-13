Vagrant.configure("2") do |config|
    config.vm.define "vm11" do |vm11|
        vm11.vm.box = "krlex/centos-awx"
        vm11.vm.hostname = "ssh1"
        vm11.vm.provider "virtualbox" do |vb|
            vb.memory = 2048
            vb.cpus = 2
        end
        vm11.vm.network :private_network, ip: "192.168.56.10"
        vm11.vm.synced_folder ".", "/vagrant", disabled: true
    end
    config.vm.define "vm22" do |vm22|
        vm22.vm.box = "centos/7"
        vm22.vm.hostname = "ssh2"
        vm22.vm.provider "virtualbox" do |vb|
            vb.memory = 2048
            vb.cpus = 2
        end
        vm22.vm.network :private_network, ip: "192.168.56.11"
        vm22.vm.synced_folder ".", "/vagrant", disabled: true
    end
    config.vm.define "vm33" do |vm33|
        vm33.vm.box = "centos/7"
        vm33.vm.hostname = "ssh3"
        vm33.vm.provider "virtualbox" do |vb|
            vb.memory = 2048
            vb.cpus = 2
        end
        vm33.vm.network :private_network, ip: "192.168.56.12"
        vm33.vm.synced_folder ".", "/vagrant", disabled: true
    end
end
