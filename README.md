# k8s_rolling_upgrade
Upgrade K8s cluster to new major version by passing VERSION as e.g 1.22 and MINOR_VERSION as e.g. 11


Requirements
------------
And existing cluster should be present and correct higher version detail should be passed in variable.

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------

See playbook/k8s_upgrade.yml and playbook/hosts.example 

License
-------

GNU General Public License v2.0

Author Information
------------------

Humbir
