Welcome to the Ansible Readme Wiki page!
This wiki mainly covers instruction for installing Ansible.

------------------------------------------------------------
### My Setup:
I have installed and configured VirtualBox, Vagrant environment, created VMs on my local MAC OS machine.
Please refer to https://github.com/dhakalanis/vagrant/blob/master/README.md

On this wiki page, I will simply install Ansible on one of the VM (name: dhakal)
All the steps and instructions are performed on my below VM.

```
vagrant@dhakal:~$ uname -a
Linux dhakal 3.13.0-145-generic #194-Ubuntu SMP Thu Apr 5 15:20:44 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
vagrant@dhakal:~$ 
```

### Actual Installation:

* Step 1: Install the software-properties-common package

`` $ sudo apt-get update && sudo apt-get install software-properties-common ``

* Step 2: Add the Ansible repository to your system

`` $ sudo apt-add-repository ppa:ansible/ansible ``

* Step 3: Install Ansible

`` $ sudo apt-get update && sudo apt-get install ansible ``

**Ansible Version Check:**
``` 
vagrant@dhakal:~$ ansible --version
ansible 2.5.2
  config file = /etc/ansible/ansible.cfg
  configured module search path = [u'/home/vagrant/.ansible/plugins/modules', u'/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python2.7/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 2.7.6 (default, Nov 23 2017, 15:49:48) [GCC 4.8.4]
vagrant@dhakal:~$ 
```


