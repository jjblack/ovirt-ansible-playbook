# oVirt configuration

This is the playbook currently in development to deploy oVirt.


## Dependencies

This playbook uses ovirt roles that are included in Ansible Galaxy. The following is a summary of [this page](https://www.ovirt.org/blog/2017/08/ovirt-ansible-roles-how-to-use.html).

Install the roles with

`ansible-galaxy install ovirt.ovirt-ansible-roles`

The easiest way for Ansible to find these roles is to change the roles directory with:

`sed -i 's|#roles_path    = /etc/ansible/roles|roles_path = /etc/ansible/roles:/etc/ansible/roles/ovirt.ovirt-ansible-roles/roles|'  /etc/ansible/ansible.cfg`

###### This page is still under development
