# How to create a AMI image with Packer.

# Purpose:

This repository's sole purpose is to demonstrate how to built a AWS with Packer.

# Technologies in use :

- Packer
- Vagrant
- VirtualBox

# How to install the pre-requisites:

- [How to install Vagrant](https://www.vagrantup.com/docs/installation/)
- [How to install VirtualBox](https://www.virtualbox.org/manual/ch02.html)

# How to use:

- Execute `git clone https://github.com/martinhristov90/packerAWS.git`
- Change into directory packerAWS with `cd packerAWS`
- Start Vagrant with VirtualBox provider by executing `vagrant up`
- Run `packer build `packer build -var 'aws_access_key=YOUR_AWS_KEY' -var 'aws_secret_key=YOUR_AWS_SECRET_KEY' templateAWS.json