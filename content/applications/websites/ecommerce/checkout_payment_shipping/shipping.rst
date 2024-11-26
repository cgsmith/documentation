========
Shipping
========

Customers can choose their shipping method from the options you provide when shopping online at
checkout.

You can offer :ref:`custom shipping options <ecommerce/shipping/custom-method>` (e.g., flat-rate
shipping, free shipping, or :doc:`Sendcloud <../../../inventory_and_mrp/inventory/shipping_receiving/setup_configuration/sendcloud_shipping>`
shipping carriers) or integrate with
:ref:`external providers <ecommerce/shipping/external-provider>` that handle the delivery, fetch
real-time rates, generate labels, and track shipments.

.. _ecommerce/shipping/external-provider:

External provider integration
=============================

To handle product delivery, you can connect your system to third-party shipping carriers like FedEx,
UPS, DHL, or local couriers. A shipping connector links your business platform to these providers,
automating communication, tracking, and shipping processes.

To enable a third-party shipping method, go to :menuselection:`Website --> Configuration -->
Settings`, scroll to the :guilabel:`Shipping` section, select the shipping provider(s) you want,
then :ref:`configure <ecommerce/shipping/configure>` them.

.. _ecommerce/shipping/configure:

Configure existing shipping methods
-----------------------------------

Once installed, you can configure your shipping methods. Go to :menuselection:`Website -->
Configuration --> eCommerce: Shipping Methods` to see the list of the :guilabel:`Delivery Methods`
available and other information, such as the :guilabel:`Provider`, whether this method is
:guilabel:`Published` on your eCommerce, in which :guilabel:`country` it is available, and more.

Click an existing delivery method to
:doc:`configure it <../../../inventory_and_mrp/inventory/shipping_receiving/setup_configuration/third_party_shipper>`.

.. _ecommerce/shipping/custom-method:

Custom shipping method
======================

To create a custom shipping method, go to :menuselection:`Website --> Configuration -->
Shipping Methods`, click :guilabel:`New` and fill in the details. Your custom shipping method may
or may not involve a provider. For example, for **flat-rate shipping** or **free shipping**, a
provider is not required, while it is needed for the following cases:

#. You want carriers different than the ones available, :doc:`Sendcloud <../../../inventory_and_mrp/inventory/shipping_receiving/setup_configuration/sendcloud_shipping>`,
   for example, allows you to use DHL but to use it, you need to create a new shipping method yourself.

#. You want the same shipping method that already exists but with different rules, such as
   "orders above 100 euros will be free".

#. You want a shipping method dedicated to one specific website.

.. tip::

   Shipping methods can be made available on **specific** websites *only*, if desired. To do so, go
   to :menuselection:`Website --> Configuration --> Settings --> Shipping Methods`, and select the
   desired **shipping method**. In the :guilabel:`Website` field, set the website you want the
   shipping method to be restrained to. Leave the field **empty** for the method to be available on
   *all* websites.
