Vagrant.configure("2") do |config|
	config.vm.provision "shell", inline: "echo Hello"
	
	config.vm.define "ad" do | ad |
		ad.vm.box = "mwrock/Windows2016"
		ad.vm.hostname = "TEST-AD1"
		ad.vm.network "private_network", ip: "10.254.1.16"
	end
	
	config.vm.define "file" do | file |
		file.vm.box = "mwrock/Windows2016"
		file.vm.hostname = "TEST-FILE1"
		file.vm.network "private_network", ip: "10.254.1.17"
	end
	
	config.vm.define "exch" do | exch |
		exch.vm.box = "mwrock/Windows2016"
		exch.vm.hostname = "TEST-EXCH1"
		exch.vm.network "private_network", ip: "10.254.1.18"
	end
	
	config.vm.define "app" do | app |
		app.vm.box = "mwrock/Windows2016"
		app.vm.hostname = "TEST-APP1"
		app.vm.network "private_network", ip: "10.254.1.19"
	end
end
