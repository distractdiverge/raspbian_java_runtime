alexlapinski.ansible_role_raspbian_java_runtime
=========

An Ansible role to install zulu java.

Role Variables
--------------
 * **java_zulu_version** - the java version (major) for zulu JRE. (e.g. 8, 11)

Example Playbook
----------------

    - hosts: servers
      roles:
         - name: alexlapinski.ansible_role_raspbian_java_runtime
           vars:
            - java_zulu_version: 8

License
-------

MIT

Author Information
------------------

Alex Lapinski - https://alexlapinski.name
