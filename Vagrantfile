Vagrant.configure("2") do |config|
  ubuntu = %w(
    precise
    trusty
    wily
    xenial
    yakkety
    zesty
    artful
    bionic
    cosmic
  )

  ubuntu.each do |vm_name|
    config.vm.define vm_name, autostart: false do |vm|
      vm.vm.box = "ubuntu/#{vm_name}64"
    end
  end
end
