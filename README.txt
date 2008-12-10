======
README
======

:Author: Marc-Aurèle Darche

:Revision: $Id$

.. sectnum::    :depth: 4
.. contents::   :depth: 4


Introduction
============

.. _TinyMCE: http://tinymce.moxiecode.com/

CPSTinyMCE is very straightforward integration of TinyMCE_ 3.2.1.1 into CPS.

TinyMCE_ is distributed under the GNU Lesser General Public License (LGPL).


Installation
============

Add the `CPSTinyMCE` product to your Zope Products directory
and then restart the Zope instance.

Then you just need to import the `CPS Tiny MCE` profile in the `portal_setup`
tool.


Building receipt
================

In this section will be explain how the CPSTinyMCE product has been created,
so you can easily create a new version based on a newer version of TinyMCE_ if
CPSTinyMCE is behind.

Steps to build:

1. Install the needed files in the `skins` directory::

     $ unzip tinymce_3_2_1_1.zip
     $ cd tinymce
     $ rm -rf examples
     $ mkdir skins
     $ mv jscripts/tiny_mce skins

2. Rename all .htm files in .htm.pt



.. Local Variables:
.. mode: rst
.. End:
.. vim: set filetype=rst:
