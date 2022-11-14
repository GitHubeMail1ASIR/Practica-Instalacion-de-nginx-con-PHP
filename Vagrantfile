# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define :proxy do |proxy|
      proxy.vm.box = "debian/bullseye64"
      proxy.vm.hostname = "proxy"
      proxy.vm.synced_folder ".", "/vagrant", disabled: true
    end
  end
