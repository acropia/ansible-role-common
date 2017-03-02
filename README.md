Role Name
=========

Install and configure common applications and settings every sysadmin needs on a CentOS Linux 7+ server.

Tools installed:
- AIDE
- arpwatch
- bind-utils (dig, host, nslookup)
- Dstat
- fail2ban
- git
- htop
- iftop
- iotop
- mailx
- man
- mtr
- Ncdu
- net-tools (netstat, etc.)
- Rootkit Hunter
- screen
- strace
- traceroute
- vim
- wget

Other settings
- Filesystem security (hidepid for /proc)
- Hosts file
- Kernel configuration
- Login defaults (password age, etc.)
- Module blacklists (USB storage, fireware, etc.)
- NTP configuration


Requirements
------------

none

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: acropia.common }

License
-------

BSD

Author Information
------------------

Jan Bouma

Acropia.nl
