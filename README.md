# Ansible Role: Nessus agent

Installs Nessus agent on supported Linux hosts.


## Requirements

TBD

## Role Variables

Below are available variables for configuring the installation and setup:

```
# Installation options:
# ---
#
# nessus_download_url: https://my-personal-dropbox/nessus.deb
#
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
         - { role: huit-academictechnology-ops.ansible-role-nessus, nessus_download_url: https://path/to/package/nessus.deb }

License
-------

MIT/BSD

Author Information
------------------

This role was created in 2020 by Colin Murtuagh as a member of the Harvard University IT Academic Technology group.
