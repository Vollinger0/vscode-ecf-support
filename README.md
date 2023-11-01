# ecf-support README

Support for the Empyrion Galactic Survival configuration file format "ecf" which is basically the worst
mix of yaml, json and all subvariants, thrown together in a mess of a format full of inconsistencies :)

Just an vscode extension quickly thrown together so scenario creators can have an easier life.

## Install
- download [the extension file](ecf-support-0.0.2.vsix)
- in VSCode -> CTRL+SHIFT+P -> "Developer: Install Extension from Location" OR
use `code --install-extension ecf-support-*.vsix`

If opening an ecf file didn't automatically select the extension already, do that yourself:
CTRL+K M -> Select ecf language - vscode should remember that setting in the future.

## Features

Basically just a simple syntax highlighting extension for ecf files. With a few intended bugs so you feel at home.

## Requirements

Just vscode.

## Extension Settings

None yet.

## Known Issues

- probably a lot

## TODOs

- [ ] support to navigate known entities, especially dialogue states in the dialogues.ecf
- [ ] format support for dialogue function blocks
- [ ] tooltip for the dialogue localization or similar

## Packaging

* make sure vsce is installed, `npm install -g @vscode/vsce`
* create the vsix file with `vsce package` for now. I may publish this as an official extension some other day.

## Release Notes

### 0.0.2
- [x] extended properties don't work properly, only the first and last are highlighted
- [x] wrong highlighting on line comments after properties and extended properties
- [x] proper childblock recognition
- [x] blocktypes with empty space ending with "Name" are highlighted wrong. who made that up.
### 0.0.1
Initial release with the most basic featureset ever. But still better than none, right?

#### by vollinger 2023
