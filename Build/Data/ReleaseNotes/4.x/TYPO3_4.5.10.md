Release Notes for TYPO3 4.5.10
==============================

This document contains information about TYPO3 version 4.5.10 which was
released on December 20th, 2011.

News
----

This release is a maintenance releases and contains bugfixes only.

Notes
-----

This release aims to fix one regressions that has been introduced with
the provious release:

-   [\#32625](https://forge.typo3.org/issues/32625): In the backend,
    custom stylesheets in the rich text editor have not been showing up
    anymore, due to a wrong file inclusion.

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    be3a2ffae007f15dbb6d94aa54767ed3  blankpackage-4.5.10.tar.gz
    3fc6dcdf3d3a35c0529f427baad57787  blankpackage-4.5.10.zip
    98ed777ec4630f2698489db19682694a  dummy-4.5.10.tar.gz
    74d2efa02264b7bbde9b3ff29c776c69  dummy-4.5.10.zip
    0dd857c61728023bb451b2f3b1ad3a6e  introductionpackage-4.5.10.tar.gz
    e38ee707b253c7f1fe9dfbdaabc5a466  introductionpackage-4.5.10.zip
    35341636722ab0d38b5bb13b6d449891  typo3_src+dummy-4.5.10.zip
    33cf393622c3b4cc2a5998ce8cc41c30  typo3_src-4.5.10.tar.gz
    71a0bdaa036dfd5b6339655965ce11dd  typo3_src-4.5.10.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.

Changelog
---------

    2011-12-20  71fbd2b                  [RELEASE] Release of TYPO3 4.5.10 (TYPO3 v4 Release Team)
    2011-12-20  f8d4623  #32626          [BUGFIX] Add SQL-comparator <> to SQL parser (Stefan Neufeind)
    2011-12-19  ce5f5a7  #31622          [BUGFIX] Invalid query part on menu rendering (Oliver Hader)
    2011-12-19  0114ceb                  Revert "[FEATURE] Add ExtJS xtype:modulepanel for BE Modules" (Ernesto Baschny)
    2011-12-18  5038a58  #30758          [BUGFIX] Login fails silently, when no backend for rsaauth is available (Steffen Gebert)
    2011-12-18  0f6f55d  #27836          [BUGFIX] EM: Uploading extensions fails with Fatal Errors (Steffen Gebert)
    2011-12-18  043f1c8  #32274          [BUGFIX] sessionTimeout for BE does not work (Mario Rimann)
    2011-12-18  33234cb  #32163          [BUGFIX] @charset must be lowercase in CSS (Markus Klein)
    2011-12-18  e87e6a3  #18176          [BUGFIX] Log password attempt with empty password (Mario Rimann)
    2011-12-18  5bccb23  #31350          [BUGFIX] Fatal error when exporting from root (Francois Suter)
    2011-12-18  b9af0ca  #28384          [FEATURE] Add ExtJS xtype:modulepanel for BE Modules (Kay Strobach)
    2011-12-18  725a8c7  #21590          [BUGFIX] Warnings in BE when using "Update reference index" (Dmitry Dulepov)
    2011-12-18  93c8987  #27969          [BUGFIX] Hide versioning icon in list when workspaces is installed (Tolleiv Nietsch)
    2011-12-17  956ecc3  #32625          [BUGFIX] Fix path check for custom RTE styles (Stanislas Rolland)
    2011-12-17  2b5a60d  #32596          [BUGFIX] Ambiguous XCLASS naming tx_em_Connection_ExtDirectServer (Steffen Gebert)
    2011-12-16  5b2516c  #21054          [BUGFIX] Random miscalculations in ImageTTFBBox (Albrecht Koehnlein)
    2011-12-16  ff97731                  [TASK] Set TYPO3 version to 4.5.10-dev (TYPO3 v4 Release Team)
    2011-12-16  07255f5                  [RELEASE] Release of TYPO3 4.5.9 (TYPO3 v4 Release Team)


