# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  
  config.vm.define :test1 do |test1| 
    # Every Vagrant virtual environment requires a box to build off of.
    test1.vm.box = "lucid32.box"
    test1.vm.box_url = "http://files.vagrantup.com/lucid32.box"
  
    # Setup Network
    # Set private network
     # Setup internal network 
    test1.vm.network :private_network, ip: "192.168.1.10"
#	config.vm.network "public_network"

 
    # Set provider related settings 
   test1.vm.provider :virtualbox do | vb | 
   vb.name="test 1"
    
    end
   end

  config.vm.define :test2  do |test2| 
    # Every Vagrant virtual environment requires a box to build off of.
    test2.vm.box = "lucid32.box"
    test2.vm.box_url = "http://files.vagrantup.com/lucid32.box"
  
    # Setup Network
    # Set private network
    # Setup internal network 
     test2.vm.network :private_network, ip: "192.168.1.11"
#	config.vm.network "public_network"

	
 
    # Set provider related settings 
    test2.vm.provider :virtualbox do | vb |
vb.name="test 2"	
  
    end
   end
end
