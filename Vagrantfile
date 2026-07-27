Vagrant.configure("2") do |config|
  config.vm.box = "debian/bookworm64"
  config.vm.hostname = "bash-lab"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "dev-sec-ops-bash-lab"
    vb.memory = 1024
    vb.cpus = 2
  end

  config.vm.synced_folder ".", "/workspace"
end
