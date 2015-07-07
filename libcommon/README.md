<img src="https://raw.githubusercontent.com/alejandroliu/pocketmine-plugins/master/Media/common.png" style="width:64px;height:64px" width="64" height="64"/>

# NAME

- Summary: aliuly's common library
- Dependency Plugins: n/a
- PocketMine-MP version: 1.4 (API:1.10.0)
- DependencyPlugins: -
- OptionalPlugins: -
- Categories: DevTools
- Plugin Access: -
- WebSite: https://github.com/alejandroliu/pocketmine-plugins/tree/master/libcommon

## Overview

<!-- //php: $v_forum_thread = "http://forums.pocketmine.net/threads/xxxxxxxxxxxxxxxx"; -->
<!-- template: prologue.md -->
<!-- Add the line: -->
<!-- php: $v_forum_thread = "http://forums.pocketmine.net/threads/XXXX"; -->


**NOTE:**

This documentation was last updated for version **0.1.0**.

Please go to
[github](https://github.com/alejandroliu/pocketmine-plugins/tree/master/libcommon)
for the most up-to-date documentation.

You can also download this plugin from this [page](https://github.com/alejandroliu/pocketmine-plugins/releases/tag/libcommon-0.1.0).

<!-- template-end -->

This plugin contains my standard library that I personally use when
writing PocketMine-MP plugins.

Contains quite a few utility functions. Available modules:

- mc - translation
- Cmd - execute PocketMine commands from a PHP module.
- MoneyAPI - supports the following economy plugins:
  - GoldStd
  - PocketMoney
  - EconomyAPI
  - MassiveEconomy
- MPMU - miscellaneous utilities
- Npc - Non-player character functionality
- PluginCallbackTask - Replacement for the CallbackTask deprecated functionaltiy
- BasicPlugin - My extensions to PluginBase
- BasicCli - My class to impelements commands and/or sub-commands
- BasicHelp - Implements help functionality for sub-commands
- PluginAsyncTask - A simple wrapper around AsyncTask
- QueryAsyncTask - An AsyncTask wrapper for MinecraftQuery

Features:

- Paginated output
- Command/Sub-command registration
- Player state management
- Config shortcuts and multi-module|feature management
- Translations
- Multiple economy supports
- API version checking
- Plugin shortcuts, etc...

It also bundles useful third party libraries:

- xPaw MinecraftQuery


For the full API documentation go to: [GitHub pages](http://alejandroliu.github.io/pocketmine-plugins/libcommon/apidocs/index.html)

## Changes

* 1.0.0: First release

## Copyright

    libcommon
    Copyright (C) 2015 Alejandro Liu
    All Rights Reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.