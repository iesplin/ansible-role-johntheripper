ansible-role-johntheripper
=========

Ansible role to install John the Ripper from the official repo for the Jumbo bleeding-edge version

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: ansible-role-johntheripper
          jtr_local_src_dir: /usr/local/src
          jtr_openmpi_support_enabled: true
          jtr_rexgen_support_enabled: false

License
-------

MIT
