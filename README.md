# Docker in Virtualbox Env

OS: macOS 10.15.7 (Intel CPU)

VMware Fusion: 12.1.2

Vagrant: 2.3.4


## Steps
```bash
git clone https://github.com/wxlee/lab-docker-env.git

cd lab-docker-env

# step up vm
vagrant up

# SSH Login
vagrant ssh
```

## Login by SSH (Only for lab)
default user / password: vagrant / vagrant

## Vagrant useful command
```bash
# Create Vagrantfile
vagrant init

# Setup or start vm (only provision once)
vagrant up

# Poweroff vm
vagrant halt

# Freeze vm
vagrant suspend

# Delete vm
vagrant destroy

# List box
vagrant box list
```
