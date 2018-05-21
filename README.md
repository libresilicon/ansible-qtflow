
# Qtflow ansible install script

This ansible script installs qtflow with all dependencies on Ubuntu 18.04 LTS. An Vagrantfile is provided to setup everything in a vm.

## Install

For initial setup run:

```
~/ansible-qtflow: vagrant up
```

This installs the vm and does ansible provisioning.

To apply changes in Vagrantfile, like other OS version, please run:

```
~/ansible-qtflow: vagrant provision
```

## Author

Stefan Helmert

