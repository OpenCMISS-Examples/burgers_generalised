===================
Burgers Generalised
===================

Burgers equation is the simplified version of the Navier-Stokes equation (by dropping the pressure term). This equation can be investigated in one spatial dimension.
The generalised form of the Burgers equation is implemented in this example.


Building the example
====================

The fortran version of the example can be configured and built with CMake::

  git clone https://github.com/OpenCMISS-Examples/burgers_generalised.git
  mkdir burgers_generalised-build
  cd burgers_generalised-build
  cmake -DOpenCMISSLibs_DIR=~/opencmiss/install/  ../burgers_generalised/
  make


Running the example
===================

Fortran version::

  cd src/fortran/
  ./burgers_generalised_fortran

The results can be visualised by running `visualiseBurgersGeneralised.cmgui <./src/fortran/visualiseBurgersGeneralised.cmgui>`_ with the `Cmgui visualiser <http://physiomeproject.org/software/opencmiss/cmgui/download>`_.


References
==========

Heinrich, J.C. and Pepper, D.W., 1999. Intermediate finite element method: fluid flow and heat transfer applications. (pg. 216)


Prerequisites
=============

There are no additional input files required for this example as it is self-contained.


License
=======

License applicable to this example is described in `LICENSE <./LICENSE>`_.
