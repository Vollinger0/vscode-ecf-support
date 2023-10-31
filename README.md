# ecf-support README

Support for the Empyrion Galactic Survival configuration file format "ecf" which is basically the worst
mix of yaml, json and all subvariants mixed together in a mess of a format full of inconsistencies :)

Just an vscode extension quickly thrown together so scenario creators can have an easier life.

## Features

Basically just a simple syntax highlighting. Has even various bugs.

## Requirements

Just vscode.

## Extension Settings

None yet.

## Known Issues

- extended key-value pairs don't work properly, only the first and last are highlighted
- blocktypes with empty space ending with "Name" are highlighted wrong. who made up that.
- probably a lot more

## TODOs

- [ ] fix issues above
- [ ] support to navigate known entities, especially dialogue states in the dialogues.ecf
- [ ] format support for dialogue function blocks
- [ ] tooltip for the dialogue localization or similar

## Release Notes

### 1.0.0

Initial release with the most basic featureset ever. But still better than none, right?

#### by vollinger 2023
