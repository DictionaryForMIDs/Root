# Introduction
DictionaryForMIDs (DfM) is a open source dictionary that is available on Java-compatible and other platforms.

# Setup

1. Clone this project via `git clone --recursive git@github.com:DictionaryForMIDs/Root.git DictionaryForMIDs`
2. Change into the Android module via `cd DictionaryForMIDs/DictionaryForMIDs_Android`
3. Rename the properties file: `mv gradle.properties.TEMPLATE gradle.properties`
4. Change into the Core module via `cd ../DictionaryForMIDs_Core`
5. Checkout the core via git-svn: `git svn clone -r686 https://svn.code.sf.net/p/dictionarymid/code/ --trunk=trunk/DictionaryForMIDs/ .`
6. Open the project folder `DictionaryForMIDs` in Android Studio, confirm to setup gradle wrapper
7. Run a gradle build via the menu, ie. `assembleDebug` to make sure the setup works

# Original README

README for the DictionaryForMIDs for Android package, version ${versionName}
This package can be downloaded from http://dictionarymid.sourceforge.net

DictionaryForMIDs comes with ABSOLUTELY NO WARRANTY


Copyright notice for the DictionaryForMIDs Java application:
============================================================

Copyright (C) 2005, 2006, 2009 Gert Nuber et al., contact via 
http://dictionarymid.sourceforge.net

This program is free software under the terms and conditions of the GPL
(GNU General Public License) version 2. See file COPYING.

The source code is also available via http://dictionarymid.sourceforge.net



Copyright notice for the dictionary:
====================================

Please refer to info-dialog and to other readme files or license files in this 
archive.
