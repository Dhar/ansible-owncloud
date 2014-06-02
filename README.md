ownCloud
======

Installs [ownCloud](http://owncloud.org/) from packages following ownCloud's installation instructions.
Admittedly, a really simple role.  Created to install ownCloud onto stripped-down OpenVZ containers.

Requirements
------------

This role was created for and tested on Ubuntu Trusty.  Please add other distributions as you see fit.

Role Variables
--------------

None, yay!

Dependencies
------------

None, bigger yay!

Usage
-----

    ansible-galaxy install garnold.owncloud

Also check the [Ansible Galaxy](https://galaxy.ansibleworks.com/intro) about page.

Example Playbook
-------------------------

Super simple:

    - hosts: owncloud
      roles:
      - { role: garnold.owncloud }

License
-------

MIT

Author Information
------------------

Gary Arnold

[GitHub project page](https://github.com/gdamjan/ansible-gitlab)
