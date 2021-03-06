=======
History
=======

Next Release
------------
- Stay tuned

2.0.0 (2016-01-01)
------------------
- BREAKING: (Internal API) ``connect.block`` removed
- BREAKING: (Internal API) ``connect.write_file`` renamed to ``connect.save``
- Feature: Rewrote the entire library to encapsulate logic
- Feature: Extendable serializer contract, to allow any config format.
- Feature: Upgrade to stable.
- Feature: Removed threading in favor of a smarter locking mechanism
- Feature: Add support for py26 and py35
- Feature: Pin dependencies
- Feature: Reorganized package and tests
- Fix: Updated doc builds
- Fix: Readme badge links
- 2.0.1: Fix: Failed deploy (travis requirements)


1.2.0 (2015-05-18)
------------------

- Feature: Improved compatibility to py27, py32, py33, py34, and pypy
- Feature: Supports multiple config files.
- Feature: Writes less, smarter logic on deciding if a write is necessary.
- Feature: Delegates writes to a background process.
- Testing: Renamed tests to be more descriptive of expectations.
- Testing: Added a bunch of tests describing different scenarios.
- Massive Refactoring

1.1.0 (2015-04-15)
------------------

- Massive improvement to documentation and presentation.

1.0.0 (2015-04-13)
------------------

- First working version.

0.1.0 (2015-04-11)
------------------

- First release on PyPI.
