Release Notes for TYPO3 CMS 7.6.4
=================================

This document contains information about TYPO3 CMS 7.6.4 which was
released on February 23rd, 2016.

News
----

This release is a combined bug fix and security release.

Notes
-----

Find more details in the security bulletins:

-   <https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2016-005/>
-   <https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2016-007/>
-   <https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2016-008/>

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    400d5f8808c1377034ddc35165ccbb18  typo3_src-7.6.4.tar.gz
    d9b4ec13fdc935445f6e85c3e3c7fdc8  typo3_src-7.6.4.zip

SHA256 checksums
----------------

    6d65008f4a71036cc6c90648f3c4019422904ff7c7d3c0f84a1695d64b8f615b  typo3_src-7.6.4.tar.gz
    04fe21245a0881ed3be1219092cc86bcba1d2fb28554e33d425814bfa5bc347e  typo3_src-7.6.4.zip

Upgrading
---------

### Upgrading from TYPO3 6.2 and from earlier versions of TYPO3 7

1.  Before you update any instance to 7.6, have a backup in place.
2.  Then uninstall any extension, that is not shipped with the core.
    This will avoid broken backend after upgrade due to removed class
    alias layer.
3.  Now download the new core and present it to your instance (by
    symlink or copied files)
4.  Use the install tool to run the upgrade wizards
5.  Use the install tool to clear each and every cache you can find,
    even opcode.
6.  Open the backend and go to the extensionmanager. When you use any
    extension without namespaces, activate the compatibility6 extension
    which can be found in the TYPO3 Extension Repository of typo3.org.
    You find further information about this extension and its purpose at
    <https://typo3.org/news/article/retaining-compatibility-to-typo3-cms-6/>
7.  Now reactivate your extensions and enjoy the brand new TYPO3 CMS 7.
8.  When you encounter compatibility problems with your extensions, look
    for the git versions around in order to find one already upgraded.
    For example realurl can be found here, until it gets released to
    TER: <https://github.com/helhum/realurl>

### Upgrading from TYPO3 7.6 / TYPO3 7 LTS

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.\
It might be required to clear all caches; the “important actions”
section in the TYPO3 Install Tool offers the accordant possibility to do
so.

Changes
-------

Here is a list of what was fixed since
[7.6.3](TYPO3_CMS_7.6.3 "wikilink"):

    2016-02-23  2b5e84e                  [RELEASE] Release of TYPO3 7.6.4 (TYPO3 Release Team)
    2016-02-23  8540f0b  #73458          [SECURITY] Limit the search results per page (Benni Mack)
    2016-02-23  83b9a83  #73450          [SECURITY] Escape output of tt_content.default (Georg Ringer)
    2016-02-23  7cf2831  #61269          [SECURITY] XML entity expansion (Benni Mack)
    2016-02-23  815ac6c  #71494          [BUGFIX] RTE Image Wizard (Markus Klein)
    2016-02-23  233db49  #73538          [BUGFIX] Check correctly for allowed localization action (Andreas Fernandez)
    2016-02-23  26d1f57  #73600          [TASK] Replace JavaScript confirm dialog in User settings (Frank Naegler)
    2016-02-22  578a6ee  #71596          [BUGFIX] IRRE child records cannot be synchronized/localized correctly (Oliver Hader)
    2016-02-22  772e930  #73607          [TASK] Remove adodb diff (Christian Kuhn)
    2016-02-22  ecf4543  #63131          [BUGFIX] feedit: Double encoding of labels (Christian Weiske)
    2016-02-22  7f4d88b  #73581          [BUGFIX] User settings: Removed call to deprecated method render() (Michael Oehlhof)
    2016-02-22  626d3ad  #73553          [BUGFIX] Add missing method getPidOfUid to RecyclerUtility (Andreas Fernandez)
    2016-02-20  0f9cbd9  #73576          [BUGFIX] Linkvalidator: Removed call to deprecated method render() (Michael Oehlhof)
    2016-02-19  e169498  #73546          [BUGFIX] Form wizard: Removed call to deprecated method render() (Michael Oehlhof)
    2016-02-19  d71f78d  #73444          [BUGFIX] Add missing new_content_element overrides in PageLayoutView (Richard Haeser)
    2016-02-19  a18d59e  #73560          [TASK] Add keyboard binding in install tool for all configuration search (Frank Naegler)
    2016-02-19  b4d340d  #73531          [BUGFIX] Avoid session file race-condition in Install Tool (Markus Klein)
    2016-02-19  090f9f3  #73505          [TASK] Make text translatable in ShortcutMenu JavaScript (Wouter Wolters)
    2016-02-19  aa08b80  #73561          [TASK] Move "Save and close" to the last position in scheduler (Andreas Fernandez)
    2016-02-19  d919443  #72782          [BUGFIX] Convert slashes in Windows paths for blacklist generation (Nicole Cordes)
    2016-02-17  ac243e7  #73521          [BUGFIX] Render correct colPos in section menus again (Daniel Goerz)
    2016-02-17  ac62c7f  #73428,#73475   [BUGFIX] Fix save and view page for a new page record (Wouter Wolters)
    2016-02-17  ebb8cc8  #73487          [BUGFIX] Don't convert labels for charsets in Extbase/Fluid (Benni Mack)
    2016-02-16  00a5c0c  #73477          [BUGFIX] Catch submit event while saving shortcut with enter (Wouter Wolters)
    2016-02-16  f0c8b1a  #73489          [BUGFIX] Use correct palettes for pages.media sys_file_references (Benni Mack)
    2016-02-16  9ace247                  [TASK] Set TYPO3 version to 7.6.4-dev (TYPO3 Release Team)


