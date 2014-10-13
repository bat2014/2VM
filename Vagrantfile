# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  
  config.vm.define :test4 do |test4| 
    # Every Vagrant virtual environment requires a box to build off of.
   # test1.vm.box = "lucid32.box"
   # test1.vm.box_url = "http://files.vagrantup.com/lucid32.box"
  test4.vm.box = "hashicorp/precise64"
    # Setup Network
    # Set private network
     # Setup internal network 
    test4.vm.network :private_network, ip: "192.168.10.10"
#	config.vm.network "public_network"

 
    # Set provider related settings 
   test4.vm.provider :virtualbox do | vb | 
   vb.name="test4"
    #  vb.customize ["modifyvm", :id, "--memory", "1024"]
     # vb.customize ["modifyvm", :id, "--name", "Frontend"]
    end

   
  end

  config.vm.define :test3  do |test3| 
    # Every Vagrant virtual environment requires a box to build off of.
  # test2.vm.box = "lucid32.box"
  #  test2.vm.box_url = "http://files.vagrantup.com/lucid32.box"
  test3.vm.box = "hashicorp/precise64"
    # Setup Network
    # Set private network
    # Setup internal network 
     test3.vm.network :private_network, ip: "192.168.10.11"
#	config.vm.network "public_network"

	
 
    # Set provider related settings 
    test3.vm.provider :virtualbox do | vb |
vb.name="test3"	
   #   vb.customize ["modifyvm", :id, "--memory", "1024"]
    #  vb.customize ["modifyvm", :id, "--name", "Backend"]
    end

    
  end
end
