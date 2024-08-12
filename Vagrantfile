Vagrant.configure("2") do |config|
    # Configuración de la primera máquina virtual
    config.vm.define "ubuntu_vm1" do |ubuntu_vm1|
      ubuntu_vm1.vm.box = "ubuntu/jammy64" # Puedes usar la versión que prefieras
      ubuntu_vm1.vm.hostname = "Server1"
      ubuntu_vm1.vm.network "private_network", ip: "192.168.56.3"
      ubuntu_vm1.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
    # Configuración de la segunda máquina virtual
    config.vm.define "ubuntu_vm2" do |ubuntu_vm2|
      ubuntu_vm2.vm.box = "ubuntu/jammy64" # Puedes usar la versión que prefieras
      ubuntu_vm2.vm.hostname = "Server2"
      ubuntu_vm2.vm.network "private_network", ip: "192.168.56.4"
      ubuntu_vm2.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  end
  