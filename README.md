<p align="center">
  <img alt="Files Logo" src="src/Files/Assets/AppTiles/StoreLogo.scale-400.png" width="100px" />
  <h1 align="center">Files</h1>
</p>

[![Build Status](https://dev.azure.com/filescommunity/Files/_apis/build/status/Build%20Pipeline?branchName=main)](https://dev.azure.com/filescommunity/Files/_build/latest?definitionId=4&branchName=main)
[![Discord](https://discordapp.com/api/guilds/725513575971684472/widget.png)](https://discord.gg/files)
<a style="text-decoration:none" href="https://www.microsoft.com/store/apps/9NGHP3DX8HDX">
    <img src="https://img.shields.io/badge/Microsoft%20Store-Download-purple.svg?style=flat-round" alt="Store link" />
</a>
<a style="text-decoration:none" href="https://files.community/download/stable">
    <img src="https://img.shields.io/badge/Sideload-Download-blue.svg?style=flat-round" alt="Sideload link" />
</a>

## What is Files?
Files is a file manager for Windows with a powerful yet intuitive design. It has features like multiple tabs, panes, columns, shell extensions in the context menu and tags.

We welcome discussions and contributions to our repository, however to help maintain a healthy community, please read our [code of conduct](https://github.com/files-community/Files/blob/main/CODE_OF_CONDUCT.md).

## FAQ
Have any questions? Check out our [documentation site](https://files.community/docs)!

## Building from source

### 1: Prerequisites

- [Git](https://git-scm.com)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) with the UWP Development Kit.

### 2: Clone the repository.

```ps
git clone https://github.com/files-community/Files
```

This will create a local copy of the repository.

### 3: Build the project

To build the app in development mode, open the sln file in Visual Studio (Files.sln) and set the Files.Package project as the startup item by right-clicking on `Files.Package` in the solution explorer & hitting ‘Set as Startup item’.

In the architecture pane, select the correct architecture for your system as Debug which should look like this:
![image](https://user-images.githubusercontent.com/39923744/148721296-2bd132d0-4a4d-4555-8f58-16b00b18ade3.png)

## Contributors

Want to contribute to this project? Feel free to open an [issue](/issues) or [pull request](/pulls). View our [Contributing guidelines](https://github.com/files-community/Files/blob/main/.github/CONTRIBUTING.md) to make sure you're up to date on the latest guidelines for contributing to the Files codebase.

## Screenshots

![Files](src/Files/Assets/FilesHome.png)
