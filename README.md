# Support for SQL language of Manifold® Release 9 in VSCode

Manifold's SQL engine includes multiple features specifically designed for spatial SQL. Works for all data, including rasters, vector, and tables. The engine is automatically CPU parallel and GPU parallel. 

## Download and install
[:floppy_disk: Click here to download VSIX](https://github.com/rkolka/sql-manifold-9/raw/master/dist/sql9.vsix "sql9.vsix")
then run `code.exe --install-extension .\sql9.vsix`.

## Features

This extension provides syntax highlighting and snippets for Manifold's SQL.

## Requirements

Scope names are chosen such that default VS Code theme (Dark+ or Light+) has a distinct color defined for the scope.

## Extension Settings

Currently there are no extension specific settings.

## Known Issues

This is an early release. Please help.

## Locally install this extension

* If `npm` not already installed, run `scoop install nodejs` if you like `scoop`, or install `npm` any other way.
* If `vsce` not already installed, run `npm install -g @vscode/vsce`.
* To start using your extension with Visual Studio Code run `vsce package -o dist/sql9.vsix` in this folder and then run `code --install-extension .\dist\sql9.vsix`.

## Release Notes

### 1.0.180

Add new function names from Manifold 9.0.180

### 0.1.8

Add `dist/sql9.vsix`

### 0.1.7

Add a snippet

### 0.1.0

Initial release of Manifold® Release 9's SQL support in VSCode


-----------------------------------------------------------------------------------------------------------
