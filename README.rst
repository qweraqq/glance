======
Glance
======

Glance is a project that defines services for discovering, registering,
retrieving and storing virtual machine images.

Use the following resources to learn more:

* `Official Glance documentation <http://docs.openstack.org/developer/glance/>`_
* `Official Client documentation <http://docs.openstack.org/developer/python-glanceclient/>`_



======
Add BOSS driver for Glance
======

This project attempts to provide a driver for Glance

Development Env
------------
* `Official documentation <http://docs.openstack.org/developer/glance/installing.html>`_
For `centos 7`::
    $ yum install git
    $ yum install python2-devel python-setuptools python-distutils-extra
    $ yum install python-webob python-eventlet
    $ yum install python-virtualenv

From `github`::
    $ git clone git://github.com/openstack/glance

Build Glance::
    $ cd glance
    $ python setup.py build

Test the build::
    $ ./run_tests.sh -s

Now you can develop with the IDE you like :)