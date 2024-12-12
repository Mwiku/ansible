# About

Automated PC setup for mundane tasks such as software installation and other configuration.

Assumes you are using a Debian-based Linux distro.

Download or clone the repo, to the PC you want to setup

First run the install_ansible script. Ensure that it is executale using sudo chmod ./install_ansible.sh

Run the ansible playbook using

```ansible-playbook local.yml --ask-become-pass

```
