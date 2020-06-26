==================
Mission and Values
==================

.. _mission:

Our mission
-----------

NetworkX aims to be the reference library for network science algorithms in
Python. We accomplish this by:

- being **easy to use and install**. We are careful in taking on new
  dependencies, and sometimes cull existing ones, or make them optional. All
  functions in our API have thorough docstrings clarifying expected inputs and
  outputs.
- providing a **consistent API**. Conceptually identical arguments have the
  same name and position in a function signature.
- **ensuring correctness**. Test coverage is close to 100% and code is reviewed by
  at least two core developers before being included in the library.
- **caring for users’ data**. We have a functional API and don't modify
  input arrays unless explicitly directed to do so.
- promoting **education in network science**, with extensive pedagogical
  documentation.

.. _values:

Our values
----------

- We are inclusive. We continue to welcome and mentor newcomers who are
  making their first contribution.
- We are community-driven. Decisions about the API and features are driven by
  our users' requirements, not by the whims of the core team. (See
  :ref:`governance`.)
- We serve scientific applications primarily, both social and natural sciences. 
- We focus on network science algorithms and graph measures primarily.
- We prefer simple readable code that uses native Python data structures
  (especially dicts) due to their consistent intuitive interface and amazing
  performance capabilities. We include interfaces to other data structures,
  especially NumPy arrays and SciPy sparse matrixes for algorithms that more
  naturally use arrays and matrixes or where time or space requirements are 
  significantly lower. Sometimes we provide two algorithms for the same result,
  one using each data structure, when pedagogy or space/time trade-offs justify
  such multiplicity.
- We value simple, readable implementations over getting every last ounce of
  performance. Readable code that is easy to understand, for newcomers and
  maintainers alike, makes it easier to contribute new code as well as prevent
  bugs. This means that we will prefer a 20% slowdown if it reduces lines of
  code two-fold, for example.
- We value education and documentation. All functions should have `NumPy-style
  docstrings <https://docs.scipy.org/doc/numpy/docs/howto_document.html>`,
  preferably with examples, as well as gallery examples that showcase how that
  function is used in a scientific application.
  Core developers take an active role in finishing documentation examples.
- We don't do magic. We prefer to educate users rather than make decisions on their
  behalf.  This does not preclude sensible defaults.

Copyright
---------

This document is modified from the `scikit-image` mission and values document.

This document is dedicated to the public domain with the Creative Commons CC0
license.
