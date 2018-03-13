Dealscoin Core integration/staging tree
=====================================

[![Build Status]: currently underdevelopment

What is Dealscoin?
----------------

Dealscoin is an experimental crypto currency that enables instant payments to
anyone, anywhere in the world.However focuses Pakistan.Dealscoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network.Dealscoin Core is the name of open source
software which enables the use of this currency.


Development Process
-------------------

Currently dealscoin is not fully developed."Master branch" is regularly built and tested, but is not guaranteed to be
completely stable.

Contribution is described in [CONTRIBUTING.md](CONTRIBUTING.md).



Testing
-------
Will be test in April

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.


**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.
