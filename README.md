# ansible-quickie

Ansible role to introduce beginners examples.
=================

This role provides a new ansible user with a small set of examples on getting 
started with ansible and its capabilities. 

Refer to the Ansible Getting Started guide for further documentation: 

http://docs.ansible.com/ansible/2.5/user_guide/intro_getting_started.html

Requirements
------------
 - SSH access on target hosts.  These examples utilize CentOS as the target hosts.
 - Internet access on the target hosts.  This is mainly to test/install updates

*This role contains two playbooks, start-lab.yml and stop-lab.yml. I developed 
this role on my workstation which contains three CentOS7 kvm/libvirt hosts. 
this is optional and added for convenience reasons.* 

Dependencies
------------

There is no role dependencies for this role.


License
-------

Apache

Author Information
------------------
Alberto Rivera Laporte <hybridpollo@gmail.com> 
