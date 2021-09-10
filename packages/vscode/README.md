# quickstarts-preview README

This WYSIWYG type extension lets you preview .yaml or .adoc quick starts compatible files.

Example .adoc file: https://github.com/patternfly/patternfly-quickstarts/blob/main/packages/dev/src/quickstarts-data/mocks/asciidoc/TEMPLATE_PROCEDURE.adoc

Example .yaml file: https://github.com/patternfly/patternfly-quickstarts/blob/main/packages/dev/src/quickstarts-data/mocks/yamls/add-healthchecks-quickstart.yaml

## Features

Open a .doc or .yaml file in VSCode, then open the command palette (Ctrl+Shift+P / Command+Shift+P) and search for `Quick Starts: Preview`.

This will render the current file into a quick start.

When you save the open .adoc or .yaml file, the quick start preview reloads to reflect that change.

## Extension Settings

[Placeholder]

## Extension development
Open up this `vscode` folder in a new window (so it's at the root)
```
yarn install
yarn dev:compile
```
Press F5, which will launch the extension development host.
It should automatically open a watch task, so code changes should be reflected.

## Release Notes

### 0.0.1

Initial release of `quickstarts-preview` extension.

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
