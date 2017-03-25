ansible-netops
===========

Playbooks for managing networks.

#Note: this is a work in progress

Requires:
    napalm         - https://github.com/napalm-automation
    napalm-ansible - https://github.com/napalm-automation/napalm-ansible

    NAPALM Modules must be in ANSIBLE_LIBRARY Path or set when calling 'ansible-playbook'

    * ansible-playbook -i inventories/testing/hosts napalm_get_facts.yml --module-path=library
