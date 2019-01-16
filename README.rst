
========
MU Build
========

.. |build_status_windows| image:: https://dev.azure.com/projectmu/mu%20pip/_apis/build/status/Build/Mu%20Pip%20Build-%20PR%20Gate%20(Windows)?branchName=master
.. |build_status_linux| image:: https://dev.azure.com/projectmu/mu%20pip/_apis/build/status/Build/Mu%20Pip%20Build%20-%20PR%20Gate%20(Linux%20-%20Ubuntu%201604)?branchName=master

|build_status_windows| Current build status for master on Windows

|build_status_linux| Current build status for master on Linux

About
=====

Provided with config file, mu_build fetches/clones dependencies then compiles every module in each package.
This is the entrypoint into the CI / Pull Request build and test infrastructure.

Version History
===============

0.3.1
-----

Main changes:
- Switching argparser to IntermediateArgParser for MuBuild script. This will preserve the assumption that sys.argv[0] is the name of the program being run.
- Added support for omnicache with --omnicache  and --reference. See feature_omnicache.md in MU_PIP_ENVIRONMENT for more information on Omnicache.

Bug fixes:
- Linted code base, enforcing a 120 character per line limit.
- Switch logging to use MuLogging.

0.3.0
-----

Updated documentation and release process.  Transition to Beta.

< 0.3.0
-------

Alpha development