# Welcome to your VS Code Extension Pack

## What's in the folder
* This folder contains all of the files necessary for your extension pack.
* `package.json` - this is the manifest file that defines the list of extensions of the extension pack.

## Get up and running straight away
* Press `F5` to open a new window with your extension loaded.
* Open `Extensions Viewlet` and check your extensions are installed.

## Make changes
* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Install your extension
* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

## Publish your extension

Taken from [vs code docs](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

Install `vsce`

```
npm install -g @vscode/vsce
```

You can use vsce to easily package and publish your extensions:

```
$ cd myExtension
$ vsce package
# myExtension.vsix generated
$ vsce publish
# <publisher id>.myExtension published to VS Code Marketplace
```

Make sure to get a [personal access token](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#get-a-personal-access-token)