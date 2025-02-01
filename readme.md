# RPG Maker MZ - VsContainer Plugin
Version: 1.1.0

1. [Installation](#1-installation)
1. [Configuration](#2-configuration)
1. [Usage](#3-usage)
1. [How does the plugin work](#4-how-does-the-plugin-work)
1. [Changes to the core script](#5-changes-to-the-core-script)

## 1. Installation 

1. Copy [VsContainer.js](./plugins/VsContainer.js) into your plugin directory
2. Activate the Plugin in **RPG Maker**
3. [Optional] if you want to use vscode intelisense also copy [VsContainer.d.ts](./plugins/VsContainer.d.ts)
  Additionally, if you don’t already have one, copy  [jsconfig.json](./jsconfig.json) into your js directory (**not the plugin directory**).

## 2. Configuration
no configuration required
## 3. Usage
  see [demo.js](./demo/plugins/demo.js)
## 4. How does the plugin work
Plugin creates a base class for containers which has the same methods as Sprite but extends from **PIXI.Container** instead of **PIXI.Sprite** and has no bitmap handling methods.
## 5. Changes to the core script
none
## 6. Troubleshooting

## 7. License
VsConvertEscapeCharacters by rpgmakerwebthickness467 is marked with CC0 1.0 Universal. To view a copy of this license, visit https://creativecommons.org/publicdomain/zero/1.0/