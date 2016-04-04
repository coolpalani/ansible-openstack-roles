Ansible Openstack Roles
=======================

How to use this repo?

1. Modify the playbook ```deploy-keystone.yaml``` to reference the variable file for the keystone installation method you want (git, rpm, docker)

2. Modify ```variables-keystone-{{ method }}.yaml``` to define the keystone configuration as you see fit

3. Run vagrant to run spawn a test vm and apply the playbook
   ```
   vagrant up
   ```
