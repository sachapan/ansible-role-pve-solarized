Role Name
=========

sachapan.pve-solarized

Requirements
------------

None aside from a Proxmox node to deploy the role on.

Role Variables
--------------

Two variables can be set:
  css_url - The location of the solarized.css file
  index_url - The example index.html.tpl file that will replace the stock Proxmox version.

The default values can be found in defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------


    - hosts: servers
      roles:
         - role: sachapan.pve-solarized 

License
-------



Author Information
------------------

https://github.com/sachapan/ansible-role-pve-solarized
