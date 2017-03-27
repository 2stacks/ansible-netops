ansible-netops
===========

Playbooks for managing networks.

#Note: this is a work in progress

Requires:
    junos-eznc     - https://github.com/Juniper/py-junos-eznc
    napalm         - https://github.com/napalm-automation
    napalm-ansible - https://github.com/napalm-automation/napalm-ansible

    NAPALM Modules must be in ANSIBLE_LIBRARY Path or set when calling 'ansible-playbook'
        * ansible-playbook -i inventories/testing/hosts napalm_get_facts.yml --module-path=library

Notes:
    * JUNOS needs to be configured with 'set system services netconf ssh'
    * IOS needs to be configured with 'file prompt quiet'
