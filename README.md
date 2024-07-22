##Ansible cloud-init Example
==========================

This repository exists to demonstrate using cloud-init and ansible
together. These playbooks may be executed directly, or can be sourced from a
repository using cloud-init's ansible module (this repo exist to test that
functionality).

hello-world.yml
---------------
This is a simple test playbook to check if it works from cloud-init

install-package.yml
-------------------
This playbook demonstrates I can install a package from cloud-init.

## Ansible playbooks
post-customizations.yml : all necessary post customizations
parameters.yaml  : containing all parameters
templates/start-firefox.j2 : start-firefox.sh template
