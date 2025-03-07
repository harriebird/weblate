.. _deployments:

Weblate deployments
===================

Weblate can be easily installed in your cloud. Please find detailed guide for your platform:

* :doc:`install/docker`
* :doc:`install/openshift`
* :doc:`install/kubernetes`

Third-party deployments for Weblate
+++++++++++++++++++++++++++++++++++

.. note::

   Following deployments are not developed or supported by Weblate team. Parts
   of the setup might vary from what is described in this documentation.

Weblate Cloudron Package
------------------------

`Cloudron <https://www.cloudron.io/>`_ is a platform for self-hosting web applications.
Weblate installed with Cloudron will be automatically kept up-to-date.
The package is maintained by the Cloudron team at their `Weblate package repo <https://git.cloudron.io/cloudron/weblate-app>`_.

.. image:: /images/cloudron.png
   :alt: Install Weblate with Cloudron
   :target: https://www.cloudron.io/button.html?app=org.weblate.cloudronapp

Weblate in YunoHost
-------------------

The self-hosting project `YunoHost <https://yunohost.org/>`_ provides a package
for Weblate. Once you have your YunoHost installation, you may install Weblate
as any other application. It will provide you with a fully working stack with backup
and restoration, but you may still have to edit your settings file for specific
usages.

You may use your administration interface, or this button (it will bring you to your server):

.. image:: /images/install-with-yunohost.png
   :alt: Install Weblate with YunoHost
   :target: https://apps.yunohost.org/app/weblate

It also is possible to use the command-line interface:

.. code-block:: sh

    yunohost app install https://github.com/YunoHost-Apps/weblate_ynh
