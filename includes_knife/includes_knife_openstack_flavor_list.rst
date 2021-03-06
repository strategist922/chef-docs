.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for Knife.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The ``flavor list`` argument is used to show a list of flavors in an |openstack| environment, including details such as ID, name, architecture, RAM, disk, and cores.

This argument has the following syntax::

   knife openstack flavor list

This argument has the following options:

``-A ID``, ``--openstack-access-key-id ID``
   |openstack-access-key-id|

``-K SECRET``, ``--openstack-secret-access-key SECRET``
   |openstack-secret-access-key|

``--openstack-api-endpoint ENDPOINT``
   |openstack-api-endpoint|

``--region REGION``
   |region openstack|

For example, enter:

.. code-block:: bash

   $ knife openstack flavor list

