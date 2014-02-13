.. QuickFF documentation master file, created by
   sphinx-quickstart on Mon Feb 10 17:45:25 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

QuickFF Documentation
#####################

Welcome to the website of QuickFF. QuickFF is a Python package developed at the 
`Center for Molecular Modeling <https://molmod.ugent.be/>`_ (CMM) to quickly 
derive accurate force fields from ab initio calculations. This website contains
a information on how to install and use QuickFF. A detailed describtion of the 
methodology used by QuickFF to derive the force fields can be found here.

How to cite QuickFF
===================

If you used QuickFF in your research, please refer to QuickFF as follows:

Installation Guide
==================

QuickFF is developed and tested on modern Linux environments. The
installation instructions below are given for a Linux system only. If you want
to use QuickFF on other operating systems such as Windows or OSX, you should
have a minimal computer geek status to get it working. We are always interested
in hearing from your installation adventures.

.. toctree::
   :maxdepth: 2
   :numbered:
   
   ig_dependencies.rst
   ig_download.rst
   ig_installation.rst

User Guide
==========

QuickFF can be used in two ways: by means of a single command or by importing it
as a Python library in an external script. Both usages are described in this 
guide.

.. toctree::
   :maxdepth: 3
   :numbered:

   ug_script.rst
   ug_library.rst

.. _seclab_tutorials:
   
Tutorials
=========

A small list of examples illustrating the basic use of QuickFF as is described
in the User Guide:

.. toctree::
   :maxdepth: 2

   tu_benzene.rst


Reference Guide
===============

A reference guide generated from the documentation strings in the source code.

Modules of QuickFF:

.. toctree::
   :maxdepth: 2
   :numbered:

   rg_system.rst
   rg_model.rst
   rg_program.rst
   rg_perturbation.rst
   rg_cost.rst
   rg_refdata.rst
   rg_terms.rst
   rg_uff.rst
   rg_ic.rst
   rg_evaluators.rst
   rg_fftable.rst
   rg_tools.rst

Scripts of QuickFF:

.. toctree::
   :maxdepth: 2 
   :numbered:
   
   rg_qffest.rst
   rg_qfftraj.rst

Contact
=======

For support and bug reports, please contact us at `louis.vanduyfhuys@ugent.be 
<louis.vanduyfhuys@ugent.be>`_.

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`