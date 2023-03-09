# Trade Wars 2002 Theme for VS Code

This is my interpretation of a Trade Wars 2002 theme as a VS Code extension.

## What's in the folder

* This folder contains all of the files necessary for the color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/tw2002-color-theme.json` - the color theme definition file.

## Quickstart

* Press `F5` to open a new window with the extension loaded.
* Open `File > Preferences > Color Themes` and pick the desired color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

### From CLI

Install dependencies, then run the build script, then install the extension itself.
`npm install && npm run build && code --install-extension trade-wars-2002-color-theme-0.0.1.vsix`

tar -xf ~/Downloads/node-v16.14.0-linux-x64.tar.xz
