.. sectnum::

========================================================================================================
Safety and Engineering Binder for HamWAN Memphis Metro Installation at the LeBonheur Children's Hospital
========================================================================================================
:Copyright: 2017 with a Creative Commons Attribution 4.0 International (CC BY 4.0) license
:Authors: Turner, Ryan
:Revision: 1
:Date: 21 April 2017
:Organization: HamWAN Memphis Metro, Inc
:Contact: netops@memhamwan.org

.. raw:: pdf

   PageBreak

.. contents:: Table of Contents

.. attention:: For service or support, contact HamWAN NOC at netops@memhamwan.org

.. raw:: pdf

   PageBreak

Introduction
============
This document exists to provide on-site reference materials about the equipment installed on premesis, especially for troubleshooting and incident response purposes. It is not meant to be a complete record of every device installed. The source of this is maintained on the HamWAN Deployment Engineering repository, and discussion of its content may be facilitated there.

Safety Warnings
---------------

.. WARNING:: **Radio Frequency Fields on roof above the elevator room exceed the FCC general public exposure limit.**
  Obey all posted signs and site guidelines for working in radio frequency environments. Contact HamWAN NOC at netops@memhamwan.org prior to approaching any microwave antenna on this site. In accordance with Federal Communications Commission rules on radio frequency emissions 47 CFR 1.1307(b)

Systems Design and Deployment
=============================

Physical Devices (Layer 1)
--------------------------

.. csv-table:: Site Assets
   :file: assets.csv
   :header-rows: 1

Network Hosts (Layer 3)
-----------------------

.. csv-table:: Addressing
   :file: ip-addresses.csv
   :widths: 40,40,20
   :header-rows: 1

Cabling Subsystem Link Record
-----------------------------

The premesis is considered a Class 1 TIA-606-B space. All physical telecommunications infrastructure is arranged such that it is TIA-606-B standards compliant [#]_.

.. csv-table:: Infrastructure Identifiers
   :file: identifiers.csv
   :widths: 20,20,60
   :header-rows: 1

.. csv-table:: Cabling Subsystem Link Record
   :file: cabling_subsystem_link_record.csv
   :header-rows: 1

Signal Survey
-------------
Work in progress...

Licensing and Permitting
========================

RF Spectrum
-----------
All transmitters at this location are operating using the FCC license below or within the U-NII FCC regulatory domain.

.. figure:: KM4ECM-FCC-License.png
  :alt: KM4ECM FCC License

  MemHamWAN's KM4ECM amateur radio license with club privileges.

.. [#] `Administration Standard for Telecommunications Infrastructure TIA-606-B <http://az776130.vo.msecnd.net/media/docs/default-source/contractors-and-bidders-library/standards-guidelines/it-standards/tia-606-b.pdf?sfvrsn=2>`_
.. footer::
  ###Page###
