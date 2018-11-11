This repo contains Vagrant file(s) to make multi-platform programming easier for tor community.

Requires Vagrant (https://www.vagrantup.com/) and VirtualBox (https://www.virtualbox.org/) installed on host machine.

Note that for shared folder to work, you need need to have VirtualBox guest additions installed. First,
you have to install vbguest plugin:

  $ vagrant plugin install vagrant-vbguest

Then, you get it to install VirtualBox Guest Additions:

  $ vagrant vbguest

Finally, you may need to reboot your Vagrant VM:

  $ vagrant reload

