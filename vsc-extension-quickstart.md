# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file in which you declare your language support and define the location of the grammar file that has been copied into your extension.
* `syntaxes/sql9.tmLanguage.json` - this is the Text mate grammar file that is used for tokenization.
* `language-configuration.json` - this is the language configuration, defining the tokens that are used for comments and brackets.

## Get up and running straight away

* Make sure the language configuration settings in `language-configuration.json` are accurate.
* Press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching your language.
* Verify that syntax highlighting works and that the language configuration settings are working.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Add more language features

* To add features such as intellisense, hovers and validators check out the VS Code extenders documentation at <https://code.visualstudio.com/docs>

## Locally install this extension

* If `npm` not already installed, run `scoop install nodejs` if you like `scoop`, or install `npm` any other way.
* If `vsce` not already installed `npm install -g vsce`
* To start using your extension with Visual Studio Code run `vsce package -o dist/sql9.vsix` in this folder and then run `code --install-extension .\dist\sql9.vsix`.
* To share your extension with the world, read on <https://code.visualstudio.com/docs> about publishing an extension.
