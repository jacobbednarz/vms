Vagrant.configure("2") do |config|
  ubuntu = %w(
    precise
    trusty
    wily
    xenial
    yakkety
    zesty
    artful
  )

  ubuntu.each do |vm_name|
    config.vm.define "ubuntu-#{vm_name}", autostart: false do |vm|
      vm.vm.box = "ubuntu/#{vm_name}64"
    end
  end
end
