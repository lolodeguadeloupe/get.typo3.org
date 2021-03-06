Release Notes for TYPO3 4.7.6
=============================

This document contains information about TYPO3 version 4.7.6 which was
released on November 8th 2012.

News
----

This release is a combined bug fix and security release.

Notes
-----

Due to security issues found in the TYPO3 Core, there was a combined
release of TYPO3 4.5.21, 4.6.14 and 4.7.6.\
Find more details in the security bulletin:
<https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2012-005/>

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    941080c55e4217c3835ab0c2f01769e9  blankpackage-4.7.6.tar.gz
    14d2322f140fe5e608cfdb58172bfe69  blankpackage-4.7.6.zip
    8082ece9f85437827f389dc4f5f9e766  dummy-4.7.6.tar.gz
    c6af67f164a332228416cb5eb3b76fe8  dummy-4.7.6.zip
    5b4a221dc621ea3f07838a2b5a87f081  governmentpackage-4.7.6.tar.gz
    5f584aeb8d597bb9adc6d3cc93b0b171  governmentpackage-4.7.6.zip
    1b780f5c28a975a8e51e55827e3aba08  introductionpackage-4.7.6.tar.gz
    ce316795b467e408667ec63a18fc522a  introductionpackage-4.7.6.zip
    b8c2ecbed19d30240b208c92a26125bb  typo3_src+dummy-4.7.6.zip
    2c73781e351384d8a030e59b8256cf59  typo3_src-4.7.6.tar.gz
    ab0b69a3a78cf1fb5ee8282a7245bae3  typo3_src-4.7.6.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.

Changes
-------

Here is a list of what was fixed since [4.7.5](TYPO3_4.7.5 "wikilink"):

    2012-11-08  54eab24                  [RELEASE] Release of TYPO3 4.7.6 (TYPO3 Release Team)
    2012-11-08  f5d3162  #42696          [SECURITY] Fix SQL injection and XSS in record history (Oliver Hader)
    2012-11-08  07c3d63  #42774          [SECURITY] XSS in TCA Tree (Oliver Hader)
    2012-11-08  7b916d0  #42776          [SECURITY] Fix potential XSS in t3lib_BEfunc::getFuncCheck (Helmut Hummel)
    2012-11-08  389452e                  [TASK] Raise submodule pointer (TYPO3 Release Team)
    2012-11-07  3f2929d  #39677          [BUGFIX] No sorting in TypoScript Object Browser when browsing (Nicole Cordes)
    2012-11-02  b69dc9d  #42281          [BUGFIX] Translated non-published page in workspace breaks live workspace (Oliver Hader)
    2012-11-02  9330ab6  #38024          [BUGFIX] Illegal string offsets in t3lib_stdgraphic (Wouter Wolters)
    2012-11-01  8098997                  [TASK] Use correct branch for travis integration build (Helmut Hummel)
    2012-11-01  24f4a8d  #37578          [BUGFIX] PHP 5.4 warning in CLI context in switch back user (Christian Kuhn)
    2012-10-31  dc73a91  #39662          [BUGFIX] RTE: Link class not always set in Firefox (Stanislas Rolland)
    2012-10-31  ba8ead7  #42046          [BUGFIX] Restore display of mount points path (Francois Suter)
    2012-10-29  fbd5057  #40733          [BUGFIX] Wrong call to TSFE in FrontendEditing (Steffen Ritter)
    2012-10-29  4bf3cca  #42054          [BUGFIX] PHP warning: open_basedir restriction (Xavier Perseguers)
    2012-10-28  19f0cbb  #42454          [BUGFIX] Fix usage of fileadminDir (Helmut Hummel)
    2012-10-27  dd20440  #42444          [TASK] Fix generation of ext_emconf.php (Wouter Wolters)
    2012-10-22  ce6ab74  #41980          [TASK] Clean-up EXT: aboutmodules, adapt to "TYPO3 CMS" (Felix Kopp)
    2012-10-22  3440228  #38699          [BUGFIX] t3lib_div::unlink_tempfile does not always work on Windows (Stanislas Rolland)
    2012-10-22  689f1fb  #33504          [BUGFIX] New form wizard not loading in IE8 (Sebastian Schawohl)
    2012-10-19  74c10e0                  [BUGFIX] Unit test for saltedpasswords fail (Xavier Perseguers)
    2012-10-18  bfb12db  #36087          [BUGFIX] RTE: Link to disabled page doesn't show in FE, link icon does (Stanislas Rolland)
    2012-10-18  9d621aa  #29685          [BUGFIX] RTE: Words containing umlauts not added to personal dictionary (Stanislas Rolland)
    2012-10-17  bd4645c  #38406          [BUGFIX] Extension Import not working with postgresql and DBAL (Ernesto Baschny)
    2012-10-16  fb87e3a                  [TASK] Set TYPO3 version to 4.7.6-dev (TYPO3 Release Team)
    2012-10-16  8b896ef                  [RELEASE] Release of TYPO3 4.7.5 (TYPO3 Release Team)


