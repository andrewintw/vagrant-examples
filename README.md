
## vagrant commands

* start
	* `vagrant up`
* stop
	* `vagrant halt`
* restart
	* `vagrant reload` (stop >> start)
* delete
	* `vagrant destroy [box_name]`


## start log


```
/drives/c/home/ws/VMs/ubuntu-18.04  vagrant.exe up

Bringing machine 'ubuntu-18.04' up with 'virtualbox' provider...
==> ubuntu-18.04: Box 'ubuntu/bionic64' could not be found. Attempting to find and install...
    ubuntu-18.04: Box Provider: virtualbox
    ubuntu-18.04: Box Version: >= 0
==> ubuntu-18.04: Loading metadata for box 'ubuntu/bionic64'
    ubuntu-18.04: URL: https://vagrantcloud.com/ubuntu/bionic64
==> ubuntu-18.04: Adding box 'ubuntu/bionic64' (v20210514.0.0) for provider: virtualbox
    ubuntu-18.04: Downloading: https://vagrantcloud.com/ubuntu/boxes/bionic64/versions/20210514.0.0/providers/virtualbox.box
    ubuntu-18.04: Download redirected to host: cloud-images.ubuntu.com
    ubuntu-18.04:
==> ubuntu-18.04: Successfully added box 'ubuntu/bionic64' (v20210514.0.0) for 'virtualbox'!
==> ubuntu-18.04: Importing base box 'ubuntu/bionic64'...
==> ubuntu-18.04: Matching MAC address for NAT networking...
==> ubuntu-18.04: Setting the name of the VM: vbox-ubuntu-18.04
==> ubuntu-18.04: Clearing any previously set network interfaces...
==> ubuntu-18.04: Preparing network interfaces based on configuration...
    ubuntu-18.04: Adapter 1: nat
    ubuntu-18.04: Adapter 2: bridged
==> ubuntu-18.04: Forwarding ports...
    ubuntu-18.04: 22 (guest) => 2201 (host) (adapter 1)
==> ubuntu-18.04: Running 'pre-boot' VM customizations...
==> ubuntu-18.04: Booting VM...
==> ubuntu-18.04: Waiting for machine to boot. This may take a few minutes...
    ubuntu-18.04: SSH address: 127.0.0.1:2201
    ubuntu-18.04: SSH username: vagrant
    ubuntu-18.04: SSH auth method: private key
    ubuntu-18.04: Warning: Connection aborted. Retrying...
    ubuntu-18.04: Warning: Connection reset. Retrying...
    ubuntu-18.04:
    ubuntu-18.04: Vagrant insecure key detected. Vagrant will automatically replace
    ubuntu-18.04: this with a newly generated keypair for better security.
    ubuntu-18.04:
    ubuntu-18.04: Inserting generated public key within guest...
    ubuntu-18.04: Removing insecure key from the guest if it's present...
    ubuntu-18.04: Key inserted! Disconnecting and reconnecting using new SSH key...
==> ubuntu-18.04: Machine booted and ready!
==> ubuntu-18.04: Checking for guest additions in VM...
    ubuntu-18.04: The guest additions on this VM do not match the installed version of
    ubuntu-18.04: VirtualBox! In most cases this is fine, but in rare cases it can
    ubuntu-18.04: prevent things such as shared folders from working properly. If you see
    ubuntu-18.04: shared folder errors, please make sure the guest additions within the
    ubuntu-18.04: virtual machine match the version of VirtualBox you have installed on
    ubuntu-18.04: your host and reload your VM.
    ubuntu-18.04:
    ubuntu-18.04: Guest Additions Version: 5.2.42
    ubuntu-18.04: VirtualBox Version: 6.0
==> ubuntu-18.04: Setting hostname...
==> ubuntu-18.04: Configuring and enabling network interfaces...
==> ubuntu-18.04: Mounting shared folders...
    ubuntu-18.04: /vagrant => C:/home/ws/VMs/ubuntu-18.04
==> ubuntu-18.04: Running provisioner: shell...
    ubuntu-18.04: Running: inline script
    ubuntu-18.04: *** config timezone ***
    ubuntu-18.04: *** linking /bin/sh to bash instead of dash ***
    ubuntu-18.04: Removing 'diversion of /bin/sh to /bin/sh.distrib by dash'
    ubuntu-18.04: Adding 'diversion of /bin/sh to /bin/sh.distrib by bash'
    ubuntu-18.04: Removing 'diversion of /usr/share/man/man1/sh.1.gz to /usr/share/man/man1/sh.distrib.1.gz by dash'
    ubuntu-18.04: Adding 'diversion of /usr/share/man/man1/sh.1.gz to /usr/share/man/man1/sh.distrib.1.gz by bash'
==> ubuntu-18.04: Running provisioner: shell...
    ubuntu-18.04: Running: inline script
    ubuntu-18.04: *** update apt-repository ***
    ubuntu-18.04: *** installing useful pkgs ***
    ubuntu-18.04: Selecting previously unselected package lftp.
    ubuntu-18.04: (Reading database ...
    ubuntu-18.04: (Reading database ... 5%
    ubuntu-18.04: (Reading database ... 10%
    ubuntu-18.04: (Reading database ... 15%
    ubuntu-18.04: (Reading database ... 20%
    ubuntu-18.04: (Reading database ... 25%
    ubuntu-18.04: (Reading database ... 30%
    ubuntu-18.04: (Reading database ... 35%
    ubuntu-18.04: (Reading database ... 40%
    ubuntu-18.04: (Reading database ... 45%
    ubuntu-18.04: (Reading database ... 50%
    ubuntu-18.04: (Reading database ... 55%
    ubuntu-18.04: (Reading database ... 60%
    ubuntu-18.04: (Reading database ... 65%
    ubuntu-18.04: (Reading database ... 70%
    ubuntu-18.04: (Reading database ... 75%
    ubuntu-18.04: (Reading database ... 80%
    ubuntu-18.04: (Reading database ... 85%
    ubuntu-18.04: (Reading database ... 90%
    ubuntu-18.04: (Reading database ... 95%
    ubuntu-18.04: (Reading database ... 100%
    ubuntu-18.04: (Reading database ...
    ubuntu-18.04: 60017 files and directories currently installed.)
    ubuntu-18.04: Preparing to unpack .../lftp_4.8.1-1ubuntu0.2_amd64.deb ...
    ubuntu-18.04: Unpacking lftp (4.8.1-1ubuntu0.2) ...
    ubuntu-18.04: Selecting previously unselected package tree.
    ubuntu-18.04: Preparing to unpack .../tree_1.7.0-5_amd64.deb ...
    ubuntu-18.04: Unpacking tree (1.7.0-5) ...
    ubuntu-18.04: Selecting previously unselected package unzip.
    ubuntu-18.04: Preparing to unpack .../unzip_6.0-21ubuntu1.1_amd64.deb ...
    ubuntu-18.04: Unpacking unzip (6.0-21ubuntu1.1) ...
    ubuntu-18.04: Setting up tree (1.7.0-5) ...
    ubuntu-18.04: Setting up unzip (6.0-21ubuntu1.1) ...
    ubuntu-18.04: Setting up lftp (4.8.1-1ubuntu0.2) ...
    ubuntu-18.04: Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
    ubuntu-18.04: Processing triggers for mime-support (3.60ubuntu1) ...
==> ubuntu-18.04: Running provisioner: shell...
    ubuntu-18.04: Running: inline script
    ubuntu-18.04: eth1: error fetching interface information: Device not found
    ubuntu-18.04: *** ip address:  ***

==> ubuntu-18.04: Machine 'ubuntu-18.04' has a post `vagrant up` message. This is a message
==> ubuntu-18.04: from the creator of the Vagrantfile, and not from Vagrant itself:
==> ubuntu-18.04:
==> ubuntu-18.04: *** config.vm.was started :-) ***
```