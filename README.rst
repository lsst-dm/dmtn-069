.. image:: https://img.shields.io/badge/dmtn--069-lsst.io-brightgreen.svg
   :target: https://dmtn-069.lsst.io
.. image:: https://travis-ci.org/lsst-dm/dmtn-069.svg
   :target: https://travis-ci.org/lsst-dm/dmtn-069
..
  Uncomment this section and modify the DOI strings to include a Zenodo DOI badge in the README
  .. image:: https://zenodo.org/badge/doi/10.5281/zenodo.#####.svg
     :target: http://dx.doi.org/10.5281/zenodo.#####

####################################################
Report on Winter 2014 Production: Image Differencing
####################################################

DMTN-069
========

The goals of this Winter 2014 (W14) task are to investigate the
effects of differential chromatic refraction (DCR) on the rate of
false positives in image differences.  We quantify this using a suite
of image simulations that contain no intrinsic variability, and run
the images through the LSST Data Management image subtraction
pipeline, which includes detection and measurement of false positives
(both positive--going and negative--going) in the differences.  As
demonstrated in a similar analysis in Winter 2013 (W13), we are able
to achieve a false detection rate consistent with random Gaussian
fluctuations in the background in the absence of DCR.

The support code for this report can be found at https://github.com/lsst-dm/W14ImageDifferencing

**Links:**

- Publication URL: https://dmtn-069.lsst.io
- Alternative editions: https://dmtn-069.lsst.io/v
- GitHub repository: https://github.com/lsst-dm/dmtn-069
- Build system: https://travis-ci.org/lsst-dm/dmtn-069
- Test code: https://github.com/lsst-dm/W14ImageDifferencing

Build this technical note
=========================

You can clone this repository and build the technote locally with Latex.
You must have `lsst-texmf`_ installed.

.. code-block:: bash

   git clone https://github.com/lsst-dm/dmtn-069
   cd dmtn-069
   make


Editing this technical note
===========================

You can edit the ``DMTN-069.tex`` file, which is a latex document.

Remember that images and other types of assets should be stored in the ``_static/`` directory of this repository.
See ``_static/README.rst`` for more information.

The published technote at https://dmtn-069.lsst.io will be automatically rebuilt whenever you push your changes to the ``master`` branch on `GitHub <https://github.com/lsst-dm/dmtn-069>`_.

****

Copyright 2014 University of Washington

This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/.

.. _this repo: ./DMTN-069.tex
.. _lsst-texmf: https://lsst-texmf.lsst.io
