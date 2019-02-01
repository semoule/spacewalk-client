Ansible role for registering a system as a Spacewalk client.

Set variables *spw_server* and *spw_activation_key* (and override *spw_cert_rpm* if necessary) in _defaults/main.yml_ before running.

Example playbook:

    - hosts: all
      become: True
      roles:
        - spacewalk-client



