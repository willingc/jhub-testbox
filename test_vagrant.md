# Test Environment using Vagrant

## Install

- Install Vagrant and virtualbox
- Make `testbox` directory
```
mkdir testbox
cd testbox
```

- Add a box using `vagrant box add {provider/boxname}` For example,
  `vagrant box add ubuntu/trusty64` Atlas is a good source for boxes.

- Create the default virtual server test box `vagrant init {provider/boxname}` For example,
  `vagrant init ubuntu/trusty64`

- Boot the test server `vagrant up`

## Vagrant refresher

`vagrant up` - start

`vagrant halt` - stop

`vagrant destroy` - delete

`vagrant ssh` - ssh from directory with Vagrantfile

`vagrant ssh-config` - ssh details to login from other locations
