Qt 4 for Headless Systems
-------------------------

This repository contains Debian packaging files for a version of Qt 4 that
runs on headless systems, such as servers, embedded devices or other systems
without displays. For example, it is currently used to perform rendering of
meteorological data as part of a Web Map Service (WMS) installation.

To build a version of Qt for this purpose, follow the instructions given on
this page:

  https://diana.wiki.met.no/doku.php?id=batch_diana_on_headless_systems

Note that not all Qt 4 libraries and features are built in this configuration.
This is because, for the WMS installation, we are only interested in using Qt
as a display and utility library.
