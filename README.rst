=============================
climpred-cloud-demo
=============================

Try `climpred <climpred.readthedocs.io/>`_ on CMIP6 DCPP output in the cloud.

.. image:: https://i.imgur.com/HPOdOsR.png

`climpred <climpred.readthedocs.io/>`_ is an xarray wrapper for analysis of ensemble forecast models for climate prediction.

Try these notebooks on pangeo.binder.io_ : |Binder|

See http://pangeo.io for more information.

Features
--------

* access CMIP6 data in the cloud:

  - DCPP hindcast
  - optional: DCPP assimilation
  - historical

* calculate skill with `climpred <climpred.readthedocs.io/>`_
* bootstrapping significant skill with `climpred <climpred.readthedocs.io/>`_

Todo
----

* get useful number of workers and memory
* get regridding done lazily
* get bootstrapping scaling with dask

.. _pangeo.binder.io: http://binder.pangeo.io/

.. |Binder| image:: http://binder.pangeo.io/badge.svg
    :target: http://binder.pangeo.io/v2/gh/aaronspring/climpred_cloud_demo/master


.. image:: https://binder.pangeo.io/badge_logo.svg
   :target: https://binder.pangeo.io/v2/gh/aaronspring/climpred-cloud-demo/master?urlpath=lab?filepath=notebooks%2Fclimpred_DCPP_cloud.ipynb
