# README

>**Important:** Once installed the checker will only update if you add the setting `"spellMD.enable": true` to your `.vscode\settings.json` file.

This README covers off:
* [Functionality](#functionality)
* [Install](#install)
* [Run and Configure](#run-and-configure)
* [Known Issues/Bugs](#known-issuesbugs)
* [Backlog](#backlog)
* [How to Debug](#how-to-debug)

# Functionality

Load up a Markdown file and get highlights and hovers for existing issues.  Checking will occur as you type in the document.

![Underscores and hovers](https://gitlab.com/username/repository/-/raw/main/images/SpellMDDemo1.gif)

The status bar lets you quickly navigate to any issue and you can see all positions in the gutter.

[![Jump to issues](https://gitlab.com/username/repository/-/raw/main/images/SpellMDDemo2.gif)](http://shouldnottouchthis/)
[![Jump to issues](https://gitlab.com/username/repository/-/raw/main/images/SpellMDDemo2.gif)](https://gitlab.com/username/repository/-/blob/main/monkey)
![](https://gitlab.com/username/repository/-/raw/main/images/SpellMDDemo2.gif)
<img src="https://gitlab.com/username/repository/-/raw/main/images/myImage.gif">

The `spellMD.json` config file is watched so you can add more ignores or change mappings at will.

![Add to dictionary](https://gitlab.com/username/repository/-/raw/main/images/SpellMDDemo3.gif)

![issue](https://gitlab.com/username/repository/-/raw/main/issue)

[mono](https://gitlab.com/username/repository/-/blob/main/monkey)
[not](http://shouldnottouchthis/)
[Email me](mailto:example@example.com)

# Install
This extension is published in the VS Code Gallery.  So simply hit 'F1' and type 'ext inst' from there select `SpellMD` and follow instructions.


To clone the extension and load locally...

```
git clone https://github.com/Microsoft/vscode-SpellMD.git
npm install
tsc
```

>**Note:** TypeScript 1.6 or higher is required you can check with `tsc -v` and if you need to upgrade then run `npm install -g typescript`.
