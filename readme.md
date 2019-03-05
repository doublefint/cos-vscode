[![Known Vulnerabilities](https://snyk.io/test/github/doublefint/vscode-cos/badge.svg)](https://snyk.io/test/github/doublefint/vscode-cos) [![Gitter](https://img.shields.io/badge/chat-on%20telegram-blue.svg)](https://t.me/joinchat/FoZ4MxJTrP8FaYs1_iFgUQ)

# vscode-cos (deprecated)

Note: This extension has been deprecated in favor of the [vscode-objectscript](https://marketplace.visualstudio.com/items?itemName=daimor.vscode-objectscript).

---

Initial [Cache](http://www.intersystems.com/our-products/cache/cache-overview/) ObjectScript ( COS ) language support for Visual Studio Code

## Features

- Initial InterSystems ObjectScript code highlighting support.
  ![example](images/screenshot.png)
- Export existing sources to the working directory: press Ctrl+Shift+P, type 'COS', press Enter.
- Save and compile a class: press Ctrl+F7 or select "COS: Save and compile" from Ctrl+Shift+P menu.

## Installation

Install [Visual Studio Code](https://code.visualstudio.com/) first.
Open VSCode. Go to extensions and search for "ObjectScript" like it is shown on the attached screenshot and install it.
Or install from ObjectScript extension page on [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=doublefint.vscode-cos)

## Configure connection

To be able to use many plugin features, you need to configure the connection to Caché server first.

- Find a 'cos.conn' section in workspace settings (File - Preferences - Settings)
- Change settings according to your Caché instance and reload VSCode ( as temporary solution )
- You will see Caché-related output in "Output" while switched to "cos" channel (right drop-down menu on top of the output window)

## Notes

For Caché instance with maximum security level, add '%Development' role for '/api/atelier/' web-application ( [More](https://community.intersystems.com/post/using-atelier-rest-api) )

Language support based on https://github.com/RustamIbragimov/atom-language-cos
