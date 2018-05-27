Vagrant.configure("2") do |config|
  config.vm.define "ubuntu-trusty", autostart: false do |web|
    web.vm.box = "ubuntu/trusty64"
  end

  config.vm.define "ubuntu-xenial", autostart: false do |db|
    db.vm.box = "ubuntu/xenial64"
  end
end
