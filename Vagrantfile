# https://gist.github.com/niw/bed28f823b4ebd2c504285ff99c1b2c2

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.provider :virtualbox do |v|
    v.gui = true
    v.memory = 8192
  end

  config.vm.synced_folder ".", "/vagrant", type: "virtualbox"
  config.vm.provision :shell, inline: "sudo apt update -y"
  config.vm.provision :shell, inline: "sudo apt upgrade -y"
  config.vm.provision :shell, inline: "sudo apt install -y --no-install-recommends ubuntu-desktop"
  config.vm.provision :shell, inline: "sudo apt install -y --no-install-recommends virtualbox-guest-dkms virtualbox-guest-utils virtualbox-guest-x11"
  config.vm.provision :shell, inline: "sudo usermod -a -G sudo vagrant"
  config.vm.provision :shell, inline: "sudo shutdown -r now"
end
