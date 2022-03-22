# Lint information

Repo is linted with `ansible-lint`.

# Initial Lab Environment Setup (MacOS)

## System preparation

1. Install rsync: `brew install rsync`
2. Install VirtualBox
3. Install Vagrant using command: `brew install vagrant`
4. Install Vagrant plugins `vagrant-share` and `vagrant-vbguest` using command: `vagrant plugin install <plugin_name>`
5. Run command: `vagrant up` to start VMs

## VMs preparation

Connect to all nodes and do following:

1. Set locale using command: `localectl set-locale LANG=en_US.UTF-8`
2. Switch to CentOS Stream 8:
    - `dnf --disablerepo '*' --enablerepo=extras swap centos-linux-repos centos-stream-repos`
    - `dnf distro-sync`
3. Install EPEL release: `yum install epel-release`

## Usage

Run `vagrant rsync-auto` to keep working folder synced.
