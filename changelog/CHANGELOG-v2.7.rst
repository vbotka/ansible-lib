====================================
vbotka.ansible_lib 2.7 Release Notes
====================================

.. contents:: Topics


2.7.2
=====

Release Summary
---------------

Major Changes
-------------

Minor Changes
-------------
* Tasks formatting unified.
* Update debug tasks. Add var debug2 (default=false).


2.7.1
=====

Release Summary
---------------
Update README.


2.7.0
=====

Release Summary
---------------
Ansible 2.18 update

Major Changes
-------------
* Supported FreeBSD 13.4, 13.5, 14.2, 14.3

Minor Changes
-------------
* Add .gitignore to git.
* Comments formatting unified.
* Tasks formatting unified.

Bugfixes
--------

Breaking Changes / Porting Guide
--------------------------------
* Deprecated al_bsd_service_facts. Use the module vbotka.freebsd.service instead.
