===================================
Nodes
===================================

.. include:: ../../swaps/swap_desc_a.txt
.. include:: ../../swaps/swap_desc_b.txt
.. include:: ../../swaps/swap_desc_c.txt
.. include:: ../../swaps/swap_desc_d.txt
.. include:: ../../swaps/swap_desc_e.txt
.. include:: ../../swaps/swap_desc_f.txt
.. include:: ../../swaps/swap_desc_g.txt
.. include:: ../../swaps/swap_desc_h.txt
.. include:: ../../swaps/swap_desc_i.txt
.. include:: ../../swaps/swap_desc_j.txt
.. include:: ../../swaps/swap_desc_k.txt
.. include:: ../../swaps/swap_desc_l.txt
.. include:: ../../swaps/swap_desc_m.txt
.. include:: ../../swaps/swap_desc_n.txt
.. include:: ../../swaps/swap_desc_o.txt
.. include:: ../../swaps/swap_desc_p.txt
.. include:: ../../swaps/swap_desc_q.txt
.. include:: ../../swaps/swap_desc_r.txt
.. include:: ../../swaps/swap_desc_s.txt
.. include:: ../../swaps/swap_desc_t.txt
.. include:: ../../swaps/swap_desc_u.txt
.. include:: ../../swaps/swap_desc_v.txt
.. include:: ../../swaps/swap_desc_w.txt
.. include:: ../../swaps/swap_desc_x.txt
.. include:: ../../swaps/swap_desc_y.txt
.. include:: ../../swaps/swap_desc_z.txt
.. include:: ../../swaps/swap_http.txt
.. include:: ../../swaps/swap_names.txt
.. include:: ../../swaps/swap_notes.txt

.. include:: ../../includes_node/includes_node.rst

.. include:: ../../includes_node/includes_node_name.rst

.. include:: ../../includes_node/includes_node_manage.rst

The following sections discuss these elements (and their various sub-components) in more detail:

* Cloud vs. Physical Nodes
* |chef client|
* The |chef| run
* Ohai

Cloud vs. Physical Nodes
=====================================================
.. include:: ../../includes_node/includes_node_cloud.rst

.. include:: ../../includes_node/includes_node_physical.rst


|chef client|
=====================================================
.. include:: ../../includes_chef/includes_chef_client.rst

|ssl| Certificates
-----------------------------------------------------
.. include:: ../../includes_node/includes_node_certificate.rst

**jamescott: someone needs to explain how the security works between the node and the server. I know it uses SSL and that signed headers + private/public keys are used. This (probably) needs to be excised from the Chef Essentials docs and moved into a Chef Security collection of topics. Or something.**

Signed Headers
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_security/includes_security_signed_header_authentication.rst

|chef validator|
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_security/includes_security_chef_validator.rst


The |chef| Run
=====================================================
SEE INDEX_NEW. NEEDS UPDATING AND NEW DIAGRAM. IN JAMES' QUEUE.


|ohai|
=====================================================
.. include:: ../../includes_ohai/includes_ohai.rst

Automatic Attributes
-----------------------------------------------------
.. include:: ../../includes_ohai/includes_ohai_automatic_attribute.rst

|ohai| Attribute List
-----------------------------------------------------
.. include:: ../../includes_ohai/includes_ohai_attribute_list.rst

Handlers
=====================================================
.. include:: ../../includes_handler/includes_handler.rst

Handler Properties
-----------------------------------------------------
.. include:: ../../includes_handler/includes_handler_properties.rst

Writing a Handler
-----------------------------------------------------
.. include:: ../../includes_handler/includes_handler_write.rst

Example: Send email when a |Chef| run fails
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_handler/includes_handler_write_example_send_email.rst

Installing and Configuring a Handler
-----------------------------------------------------
.. include:: ../../includes_handler/includes_handler_install.rst

|lwrp chef handler|
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_handler/includes_handler_install_from_cookbook.rst

Manual Install
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_handler/includes_handler_install_manual.rst

Distributing Handlers
-----------------------------------------------------
.. include:: ../../includes_handler/includes_handler_distribute.rst

Available Handlers
-----------------------------------------------------
.. include:: ../../includes_handler/includes_handler_available.rst

|opscode|: JsonFile Handler
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_handler/includes_handler_available_jsonfile.rst

Community: Open Source Handlers
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_handler/includes_handler_available_community.rst