
========
MU Build
========

**THIS PROJECT IS NO LONGER ACTIVE** - ACTIVE WORK HAS MOVED TO https://github.com/tianocore/edk2-pytool-extensions

About
=====

Provided with config file, mu_build fetches/clones dependencies then compiles every module in each package.
This is the entrypoint into the CI / Pull Request build and test infrastructure.

Version History
===============

0.3.3-dev
-----

Main changes:
- N/A

Bug fixes:
- Emitted fewer critical events and instead using PROGRESS level



0.3.2
-----

Main changes:
- Enabling ARM as a supported architecture.

Bug fixes:
- N/A

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
