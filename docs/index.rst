
HTCondor Python module documentation
====================================

The HTCondor python modules aim to expose a high-quality, Pythonic interface
to the HTCondor client libraries.  They utilize the same C++ libraries as
HTCondor itself, meaning they have nearly the same behavior as the command line
tools.  As the python modules are shipped with HTCondor itself, this
documentation focuses on references and tutorials on how to use the modules,
rather than an install how-to.

.. note:: This work should be considered experimental (its aim is to be better-formatted
   and more intuitive); the `upstream documentation <http://research.cs.wisc.edu/htcondor/manual/current/PythonBindings.html>`_
   should be considered authoritative.

Introductory Tutorial
---------------------

Here, you will learn the basics of the python bindings and how to use them.  This introduction provides quick overview of
the major components.  Each learning module is meant to be done in sequence.  Start here if you have never used the bindings before.

.. toctree::
   :maxdepth: 2

   classad_intro
   htcondor_intro
   job_management_intro

Advanced Tutorials
------------------

The advanced tutorials are in-depth looks at specific pieces of the Python modules; each is meant to be stand-alone and
only should require knowledge from the introductory tutorial.

.. toctree::
   :maxdepth: 2

   advanced_schedd.rst
   scalable_job_tracking.rst
   interacting_with_daemons.rst

Module Reference
----------------

.. toctree::
   :maxdepth: 2

   htcondor
   classad


:ref:`genindex`

