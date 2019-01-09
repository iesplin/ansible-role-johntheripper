ansible-role-johntheripper
=========

Ansible role to install John the Ripper from the official repo for the Jumbo bleeding-edge version

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: ansible-role-johntheripper
          jtr_local_src_dir: /usr/local/src
          jtr_openmpi_support_enabled: true
          jtr_rexgen_support_enabled: false

License
-------

MIT
