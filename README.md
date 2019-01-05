# vagrant-minix-pkgsrc: a Vagrant box with MINIX + pkgsrc

# VAGRANT CLOUD

https://app.vagrantup.com/mcandre/boxes/vagrant-minix-pkgsrc

# EXAMPLE

```console
$ vagrant up
$ vagrant ssh -c "cd /usr && su root -c \"make pkgsrc-update\""
...
```

# RUNTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider

## Recommended

* [vagrant-rsync-back](https://github.com/smerrill/vagrant-rsync-back) assists in copying artifacts from the guest to the host

# BUILDTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider
* [make](https://www.gnu.org/software/make/)

# EXPORT

```console
$ make vagrant-minix-pkgsrc.box
```
