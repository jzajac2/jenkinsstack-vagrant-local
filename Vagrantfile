# TODO: can the server/slave/clientgui stack be provisioned as muliple machine vagrant config?
Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.box_check_update = false

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "512"
    vb.gui = true
  end

  #  config.vm.provision "ansible" do |ansible|
  #    ansible.playbook = ""
  #  end
end
