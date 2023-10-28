# VS Code Extension

## What's in the folder

* `package.json` - manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/Caelum-color-theme.json` - color theme definition file.

## running straight away

* Press `F5` to open a new window with extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme. (One available currently)
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window. (If pull request is accepted)

## Adopt theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

## Install extension

* To start using extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* Publishing is against MIT LICENSE without author permission.
