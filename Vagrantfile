Vagrant.configure("2") do |config|
    config.vm.box = "mcandre/minix"
    config.vm.box_version = "0.0.1"

    config.vm.provision "shell", path: "bootstrap.sh"

    # Fix vagrant package
    config.ssh.insert_key = false
end
