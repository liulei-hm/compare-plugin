Compare plugin for Notepad++
------------

A very useful diff plugin to show the difference between:
-  2 files (side by side)
-  Diff against Git
-  Diff against SVN
-  Diff since last Save

Build Status
------------

- AppVeyor `VS2013` and `VS2015`  [![Build status](https://ci.appveyor.com/api/projects/status/github/jsleroy/compare-plugin?svg=true)](https://ci.appveyor.com/project/jsleroy/compare-plugin)
- Travis '[mingw-w64](https://mingw-w64.org)' cmake build
[![Build Status](https://travis-ci.org/jsleroy/compare-plugin.svg?branch=master)](https://travis-ci.org/jsleroy/compare-plugin)

Build Compare plugin for Notepad++ from source:
-------------------------------

 1. Open [`plugin_compare\compare-plugin\projects\2013\Compare.vcxproj`](https://github.com/jsleroy/compare-plugin/blob/master/projects/2013/Compare.vcxproj)
 2. Build Compare plugin [like a normal Visual Studio project](https://msdn.microsoft.com/en-us/library/7s88b19e.aspx). Available platforms are x86 win32 and x64 for Unicode Release and Debug.
 3. x64 builds currently just have beta status, report issues at [GitHub](https://github.com/jsleroy/compare-plugin/issues).

Installation:
----------

To install the plugin manually for usage with Notepad++, copy ComparePlugin.dll and ComparePlugin subfolder
into the plugins directory (`Notepad++ installation dir`)\Notepad++\Plugins.
The ComparePlugin subfolder contains the libs libgit2.dll and sqlite.dll for the Diff against Git and SVN.

Get Compare plugin for Notepad++ at the web:
-------------------------------

- via [PluginManager](http://docs.notepad-plus-plus.org/index.php/Plugin_Central)
- manual download from [Sourceforge](https://sourceforge.net/projects/npp-plugins/files/ComparePlugin/)
- manual download of beta versions from [Dropbox](https://www.dropbox.com/sh/f42cxkqppuapa1j/AADvlcmqoK_myRmoOpeL1yGMa?dl=0)
- manual download of continuous builds from [Appveyor](https://ci.appveyor.com/project/jsleroy/compare-plugin/history)

Additional information:
----------

- Compare plugin for Notepad++ [Contributors](https://github.com/jsleroy/compare-plugin/graphs/contributors)
- See also the [Notepad++ official site](http://notepad-plus-plus.org/) for more information.

Changelog:
----------

see [`ReleaseNotes.txt`](https://github.com/jsleroy/compare-plugin/blob/master/ReleaseNotes.txt)

TODOs:
----------

 - Description of cmake build on mingw
 - extend cmake config for vs and further generator builds
 - Correct changelog of 1.5.2, 1.5.6.8, 1.5.7
