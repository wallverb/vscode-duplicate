# Duplicate File

> Ability to duplicate files in VS Code.

![Duplicate File](https://cloud.githubusercontent.com/assets/7034281/17034766/cab5463e-4f8c-11e6-9d35-f1b9e7cf5e64.gif)

## Install

  * Press `F1` and select `Extensions: Install Extensions`.
  * Search for and select `duplicate`.

See the [extension installation guide](https://code.visualstudio.com/docs/editor/extension-gallery) for details.

## Usage

The first option:

  1. Hover on a file name in explorer.
  2. Right-click and select `Duplicate file`.
  3. Enter the new path for the duplicate.

The second option:

  1. Open the file.
  2. Press `F1` and select `Duplicate file`.
  3. Enter the new path for the duplicate.

## Keyboard shortcuts

For changes keyboard shortcuts, create a new rule in `File -> Preferences -> Keyboard Shortcuts`:

```json
{
  "key": "ctrl+shift+d",
  "command": "duplicate.execute"
}
```

## Changelog

See the [Releases section of our GitHub project](https://github.com/mrmlnc/vscode-duplicate/releases) for changelogs for each release version.

## License

This software is released under the terms of the MIT license.
