==============================
OpenStack-Ansible nspawn hosts
==============================

Ansible role that configures a host for running nspawn containers.

To clone or view the source code for this repository, visit the role repository
for `nspawn_hosts <https://github.com/openstack/openstack-ansible-nspawn_hosts>`_.

Default variables
~~~~~~~~~~~~~~~~~

.. literalinclude:: ../../defaults/main.yml
   :language: yaml
   :start-after: under the License.

Dependencies
~~~~~~~~~~~~

This role needs pip >= 7.1 installed on the target host.

Example playbook
~~~~~~~~~~~~~~~~

.. literalinclude:: ../../examples/playbook.yml
   :language: yaml
