Vagrant.configure("2") do |config|
  config.vm.define "sh" do |app|
    app.vm.provider "docker" do |d|
      d.image = "busybox"
      d.name = "sh"
      d.create_args = ["-ti"]
      d.cmd = ["sh"] 
      d.vagrant_vagrantfile = "VagrantfileDockerHost"
    end
  end
end