Accessing HP iLO interfaces from python
=======================================

This module will make it easy for you to access the Integrated Lights Out
management interface of your HP hardware. It supports iLO, iLO 2 and iLO 3 and
It uses the XML interface to access and change the iLO.

The complete API is described in the :doc:`iLO class API reference </ilo>`. All
functions return structured data based on the XML returned by the iLO. See
:doc:`the output reference </output>` for example return values.

A command line interface to this module, :doc:`hpilo_cli </cli>` makes accessing iLO
interfaces almost trivial and easy to integrate with non-python scripts.

HP, Integrated Lights out and iLO are trademarks of HP, with whom the author of
this software is not affiliated in any way other than using some of their
hardware.

See also
--------
More information about interactign with the iLO XML interface can be found in
the sample XML files provided by HP on their `TechSupport site`_.

Contents:
=========

.. toctree::
   :maxdepth: 2

   ilo
   output
   cli

.. _`TechSupport site`:  http://h20000.www2.hp.com/bizsupport/TechSupport/SoftwareDescription.jsp?lang=en&cc=us&prodTypeId=18964&prodSeriesId=4154735&swItem=MTX-9ded60bd746942e18651211f51&prodNameId=4154847&swEnvOID=4004&swLang=8&taskId=135&mode=5
