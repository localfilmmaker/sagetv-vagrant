# sagetv-vagrant
Vagrant files for setting up SageTV build environments

Vagrant provides a nice interface into provisioning and setting up containers that can be used for development.  The 2 Vagrantfile scripts that are provided, provides 32bit and a 64bit Ubunutu environment that can be used to build SageTV.

Once Vagrant is installed, you can clone this repo, and the do the following...

```
cd 32bit
vagrant up
vagrant ssh
```

Now you have 32bit environment that is capable of building SageTV Linux.  You can now clone a git repo and then build the sagetv binaries.

32bit-gui and 64bit-gui are Vagrant images that will fully provision a Linux gui, download build and install sagetv and add in a simple demo media file.  These images can be used to test GUI related parts of SageTV such as the MiniClient.

For information on setting up and using Vagrant see the Vagrant site: https://www.vagrantup.com/

Many thanks to coppit for providing the docker commands, since they provide the basis of these scripts as well

https://github.com/coppit/docker-sagetv-server


