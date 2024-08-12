Vagrant.configure("2") do |config| 
  
    # Configuración para la primera máquina
    config.vm.define "ubuntu_vm1" do |ubuntu_vm1|
        ubuntu_vm1.vm.hostname = "Server1"
        ubuntu_vm1.vm.box = "ubuntu/jammy64" 
        ubuntu_vm1.vm.network "private_network", ip: "192.168.56.3"
        ubuntu_vm1.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
    # Configuración para la segunda máquina
    config.vm.define "ubuntu_vm2" do |ubuntu_vm2|
        ubuntu_vm2.vm.hostname = "Server2"
        ubuntu_vm2.vm.box = "ubuntu/jammy64" 
        ubuntu_vm2.vm.network "private_network", ip: "192.168.56.4"
        ubuntu_vm2.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
    # Configuración para la tercera máquina
    config.vm.define "ubuntu_vm3" do |ubuntu_vm3|
        ubuntu_vm3.vm.hostname = "Server3"
        ubuntu_vm3.vm.box = "ubuntu/jammy64"   
        ubuntu_vm3.vm.network "private_network", ip: "192.168.56.5"
        ubuntu_vm3.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  end
  