Ansible Role: Matterbridge
==========================

Ansible role to deploy [Matterbridge](https://github.com/42wim/matterbridge) server on CentOS/RHEL 7.x systems


Requirements
------------

No special requirements.
Note this role requires root access; either run it in a playbook with a global `become: yes` or invoke the role in your playbook:

```yaml
- hosts: servers
  roles:
    - role: jwflory.matterbridge
      become: yes
```


Role Variables
--------------

### main.yml

To be written once this role is more stable.

### vault.yml

To be written once this role is more stable.


Dependencies
------------

None.


Example Playbook
----------------

```yaml
- hosts: matterbridge-host
  roles:
     - role: jwflory.matterbridge
```


License
-------

[BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause "The 3-Clause BSD License")


Author Information
------------------

This role was first created in 2019 by [Justin W. Flory](https://justinwflory.com/).
Find him on [GitHub](https://github.com/jwflory "Check out other things I'm working on!") and [LinkedIn](https://www.linkedin.com/in/justinwflory/ "See what I'm doing out in the world…").
