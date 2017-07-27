Vagrant.configure("2") do |config|
	config.vm.provision "shell", inline: "echo Hello"
	
	config.vm.define "ad" do | ad |
		ad.vm.box = "mwrock/Windows2016"
	end
	
	config.vm.define "file" do | file |
		file.vm.box = "mwrock/Windows2016"
	end
	
	config.vm.define "exch" do | exch |
		exch.vm.box = "mwrock/Windows2016"
	end
end
