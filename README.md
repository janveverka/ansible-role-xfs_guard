Install XFS Memory Allocation Deadlock Guard
=========

This role can be used to install a mitigation for XFS memory allocation
deadlocks. It does _not_ solve the actual cause, but can be used to
mitigate the issue for a limited time.

[![Build Status](https://travis-ci.org/Rheinwerk/ansible-role-xfs_guard.svg?branch=master)](https://travis-ci.org/Rheinwerk/ansible-role-xfs_guard)

For more details, see the accompanying blog post on the [codecentric blog](https://blog.codecentric.de).


Requirements
------------

None.


Role Variables
--------------

None.


Dependencies
------------

None.


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: xfs_guard, tags: [ 'xfs_guard' ] }

License
-------

Please see LICENSE.

Author Information
------------------

Original author is [Daniel Schneller](https://github.com/dschneller) as member of the [Rheinwerk](https://github.com/Rheinwerk) project.

