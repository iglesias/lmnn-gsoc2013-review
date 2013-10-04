lmnn-gsoc2013-review
====================

GSoC 2013 code for the project named "Implement Metric Learning Algorithms with
Applications to Metagenomics".

The main use for this repository is to ease the peer review and put together all
the code that will be uploaded as code sample.

At the end of the project, an ipython notebook was written in the form of a project
report. An static version of the notebook is can be read [here](http://nbviewer.ipython.org/6576096).
This work on the notebook started before the pencils down date on September 16th, although
a few corrections were done afterwards.

# Contents

* prototype/ : Matlab implementation used for prototyping.
* lmnn/: C++ implementation as it is in Shogun.
* distance/: Other files that had to be created in Shogun to integrate LMNN.
* tests/: Unit tests using Google C++ Testing Framework.
* examples/: Examples of use in C++, Python and Octave.

A few other minor additions that were done in Shogun (e.g. SWIG bindings for LMNN) are not
included in this repository.
