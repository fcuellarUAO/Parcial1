Vagrant.configure("2") do |config|
	config.vm.define :servidor do |servidor|
		servidor.vm.box = "bento/centos-7.8"
		servidor.vm.network "private_network", ip: "192.168.50.3", virtualbox__intnet: true
		servidor.vm.hostname = "servidor"
		servidor.vm.provider "virtualbox" do |v|
			v.memory = 512
		end
	end
end