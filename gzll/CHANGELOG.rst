.. _gzll_changelog:

Changelog
#########

.. contents::
   :local:
   :depth: 2

All notable changes to this project are documented in this file.

Main branch
***********

Support nRF5340 network core.

Added
=====

* Added the library variant for the nRF5340 network core.
* Added DPPI to glue layer.

Bug fixes
=========

* Fixed the :c:func:`nrf_gzll_init` function to avoid calling memcpy() with the same addresses.
* Applied workarounds for nRF5340 anomalies 117 and 158.

nRF Connect SDK v1.8.0
**********************

Initial release.

Added
=====

* Added the :file:`libgzll.a` library variant, in both soft-float and hard-float builds, for the following nRF52 Series SoCs:

  * nRF52810
  * nRF52811
  * nRF52820
  * nRF52832
  * nRF52833
  * nRF52840
